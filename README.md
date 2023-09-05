
# TODO:

  Melhorar resposta da exclusão do usuário
  # Colocar no snnipet do Notion a criação de alguns posts
  Estudar o tracktable e o lockable para ver se faz sentido pra gente
  Excluir JWT depois do logout
  Como permitir a recuperação de senha via e-mail
    Configurar disparo de e-mail via app

      Ambiente de Produção:
        servidor smtp (servidor de email)
        porta
        segurança (SSL, TSL, nenhuma)
        email
        senha

      Ambiente de dev
        gem Mailcatcher


  Criar um Admin
  Definir acessos só para admin

  Quando for fazer as alterações no Gethub, ver se é possível deixar as duas formas de autenticacao funcionando. Se não, reaproveitar rota de login que já estamos usando
  Dar uma olhada em outras alternativas além do JWT 


  # Trackable
  Track information about your user sign in. It tracks the following columns:

  - sign_in_count - Increased every time a sign in is made (by form, openid, oauth)

  - current_sign_in_at - A timestamp updated when the user signs in

  - last_sign_in_at - Holds the timestamp of the previous sign in

  - current_sign_in_ip - The remote ip updated when the user sign in

  - last_sign_in_ip - Holds the remote ip of the previous sign in

  # https://www.iugu.com/blog/implementando-omniauth-rails
  