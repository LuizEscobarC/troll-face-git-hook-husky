# troll-face-git-hook-husky

# Rodar os testes usando Sail e verificar erros
echo "\033[1mRodando testes com Sail...
░░░░▄▄▄▄▀▀▀▀▀▀▀▀▄▄▄▄▄▄
░░░░█░░░░▒▒▒▒▒▒▒▒▒▒▒▒░░▀▀▄
░░░█░░░▒▒▒▒▒▒░░░░░░░░▒▒▒░░█
░░█░░░░░░▄██▀▄▄░░░░░▄▄▄░░░█
░▀▒▄▄▄▒░█▀▀▀▀▄▄█░░░██▄▄█░░░█
█▒█▒▄░▀▄▄▄▀░░░░░░░░█░░░▒▒▒▒▒█
█▒█░█▀▄▄░░░░░█▀░░░░▀▄░░▄▀▀▀▄▒█
░█▀▄░█▄░█▀▄▄░▀░▀▀░▄▄▀░░░░█░░█
░░█░░▀▄▀█▄▄░█▀▀▀▄▄▄▄▀▀█▀██░█
░░░█░░██░░▀█▄▄▄█▄▄█▄████░█
░░░░█░░░▀▀▄░█░░░█░███████░█
░░░░░▀▄░░░▀▀▄▄▄█▄█▄█▄█▄▀░░█
░░░░░░░▀▄▄░▒▒▒▒░░░░░░░░░░█
░░░░░░░░░░▀▀▄▄░▒▒▒▒▒▒▒▒▒▒░█
░░░░░░░░░░░░░░▀▄▄▄▄▄░░░░░█"

echo "\033[1mSerá que vai dar erro?\033[0m";


echo "\033[1mTudo certo para o push. 🚀
⠀⠀⠀⠀⠀⣠⣶⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⣦⡄⠀⠀⠀⠀⠀⠀
⠀⠀⠀⢴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣆⠀⠀⠀⠀⠀
⠀⣠⣴⣿⣿⣿⣿⣿⣿⣿⡿⠿⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⠀⠀⠀⠀
⠠⣿⣿⣿⣿⣿⠿⠛⠉⠀⠀⠀⠀⠈⠙⣿⣿⣿⣿⣿⣿⣿⣿⡆⠀⠀⠀
⠀⢻⣿⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢿⣿⣿⣿⣿⣿⣿⣿⣧⠀⠀⠀
⠀⢠⡟⡠⠔⡦⠘⣫⣤⣄⠀⠀⠀⠀⠀⠀⠹⣿⣿⣿⣿⢟⠭⢽⡀⠀⠀
⠀⠈⢇⣴⡿⢧⡌⠙⠛⠻⠿⠿⢷⣦⠄⠀⠀⢸⣿⡿⠋⢂⠀⢀⠇⠀⠀
⠀⢠⣾⡿⠡⢄⡄⢠⠀⡴⠶⠶⠲⠷⠀⠀⠀⠈⠙⠁⠀⡆⠈⢸⡇⠀⠀
⠀⠀⢏⣴⠞⢛⣷⠀⠀⠑⠒⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠔⠉⡇⠀⠀
⠀⠀⠀⠟⠈⠜⡇⠀⠀⡀⡠⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⢠⡌⠀⠀⠀
⠀⠀⢸⠀⡈⢰⡀⢀⠤⠤⠆⠀⠑⢄⠀⢠⠀⠀⠀⠀⠀⠀⢸⠃⠀⠀⠀
⠀⠀⠘⡀⠑⠈⢁⡠⢤⣀⣶⣶⢦⣄⣤⠘⡄⠀⠀⠀⠀⢘⣿⠀⠀⠀⠀
⠀⠀⠀⠐⡜⢄⣿⣞⣉⣡⣷⣿⣾⡟⢛⠸⠀⠀⠀⠀⠀⢈⡇⠀⠀⠀⠀
⠀⠀⠀⠀⠈⢂⢻⢝⠿⠍⢓⡉⠔⠁⣸⠇⠀⠀⠀⠀⠀⡜⠇⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠡⣧⠀⠀⠀⠀⠀⠔⠝⠀⠀⠀⠀⢀⠊⠀⠰⡀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⡰⠀⠀⠀⠀⠀⠀⠀⠀⠀⢳⠄⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠈⣢⢄⠠⠔⠊⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⡌⠢⡀
⠀⠀⠀⠀⠀⠀⠀⡐⠀⢆⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠐⠀⠀
\033[0m"

