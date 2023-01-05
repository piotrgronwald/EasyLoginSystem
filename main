konta = {}
while True:
    opcje = input("Wpisz 'Zarejestruj się' albo 'Zaloguj się'\n")
    login = input("Login: ")
    haslo = input('Hasło: ')
    if opcje == 'Zarejestruj się':
        konta[login] = haslo
    elif opcje == 'Zaloguj się':
        if konta[login] == haslo:
            print('Pomyślnie zalogowano!')
            break
    else:
        print('Błąd, spróbuj ponownie')
        continue
