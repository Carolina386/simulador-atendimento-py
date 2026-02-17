fila_de_atendimento = []

while True:
    nome = input("\nQual seu nome? (ou 'sair' para encerrar): ")
    if nome.lower() == 'sair':
        print("Sistema encerrado. Até logo!")
        break

    print(f"\nOlá, {nome}! Seja bem-vindo(a) ao atendimento.")

    print("""
    Menu de opções:
    1 - Financeiro
    2 - Extrato
    3 - Suporte Técnico
    4 - Cancelamento
    5 - Falar com um de nossos atendentes (Entrar na Fila)
    6 - [MODO ATENDENTE] Chamar próximo da fila
    """)

    opcao = input("Digite a opção desejada: ")

    if opcao == "1":
        print(f"✅ {nome}, você escolheu o setor Financeiro.")
    elif opcao == "2":
        print(f"✅ {nome}, você escolheu a opção Extrato.")
    elif opcao == "3":
        print(f"✅ {nome}, você escolheu a opção Suporte Técnico.")
    elif opcao == "4":
        print(f"✅ {nome}, você escolheu a opção Cancelamento.")
    elif opcao == "5":
        fila_de_atendimento.append(nome)
        print(f"\n✅ {nome}, você foi adicionado(a) à fila de espera!")
        print(f"Pessoas na sua frente: {len(fila_de_atendimento) - 1}")
    elif opcao == "6":
        if len(fila_de_atendimento) > 0:
            proximo = fila_de_atendimento.pop(0)
            print(f"\n🔔 BOX DE ATENDIMENTO: Chamando agora {proximo}!")
        else:
            print("\n⚠️ A fila está vazia no momento.")
    else:
        print("❌ Opção inválida.")

    # Só pede resolução se não for a opção do atendente
    if opcao != "6":
        resolucao = input("\nSeu problema foi resolvido? (sim/nao): ").lower()
        if resolucao == "sim":
            print("Atendimento finalizado com sucesso!")
        else:
            print(f"Sem problemas, {nome}. Aguarde o direcionamento.")

    print(f"\n--- ESTADO DA BOX (Fila): {fila_de_atendimento} ---")