nome: Empregos para atualizar dados
    runs-on: ubuntu-latest
 passos:
  # Cartões de Resumo
 - utiliza: ações/checkout@v2
 - usa: vn7n24fzkq/github-profile-summary-cards@release
        env:
 GITHUB_TOKEN: ${{{ segredos. GITHUB_TOKEN }}
 com:
 NOME DE USUÁRIO: ${{ github.repository_owner }}

  Animação de cobra
 - usos: Platane/snk@master
        id: snake-gif
