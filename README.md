##Pseudocódigo
INICIAR

Exibir formulário com campos:
    - Nome completo
    - Email
    - Data de nascimento
    - Botão Cadastrar

Quando o usuário clicar em "Cadastrar":
    PREVENIR comportamento padrão do formulário

    Ler data de nascimento inserida pelo usuário

    CALCULAR idade com base na data de nascimento atual

    SE idade for menor que 18 anos
        Mostrar mensagem de erro: "Cadastro permitido apenas para maiores de 18 anos."
        Parar execução
    SENÃO
        Mostrar mensagem: "Redirecionando para o WhatsApp..."

        Montar link do WhatsApp com número e mensagem pré-definida

        Abrir nova aba com link do WhatsApp após 1 segundo

FIM
2. README (exemplo para o projeto)
Cadastro Clinic

Este é um formulário web simples para cadastro de usuários que verifica se o usuário tem mais de 18 anos antes de permitir o cadastro. Após a validação, o usuário é redirecionado para uma conversa no WhatsApp.

Funcionalidades

Formulário com campos para nome completo, email e data de nascimento.

Validação da idade do usuário para garantir que seja maior de 18 anos.

Mensagens claras para o usuário sobre sucesso ou erro no cadastro.

Redirecionamento automático para WhatsApp com mensagem padrão para confirmação.

Tecnologias Utilizadas

HTML5 para a estrutura da página.

CSS para estilização responsiva e amigável.

JavaScript para a lógica de validação e redirecionamento.

Como usar

Preencha o formulário com seu nome completo, email e data de nascimento.

Clique em "Cadastrar".

Se for menor de 18 anos, receberá mensagem de bloqueio.

Se for maior ou igual a 18 anos, será redirecionado ao WhatsApp para continuar o atendimento.

Personalização

Modifique o número de WhatsApp e a mensagem no arquivo HTML dentro do script JavaScript.

Ajuste o estilo no bloco CSS conforme sua identidade visual.

3. Lógica do site (explicação simples)

O usuário acessa a página e vê um formulário para preencher nome, email e data de nascimento.

Quando o botão "Cadastrar" é clicado, o JavaScript intercepta o envio do formulário para impedir que a página recarregue.

O script então pega a data de nascimento informada e calcula a idade atual do usuário.

Se o usuário tiver menos de 18 anos, uma mensagem de erro aparece e o cadastro não continua.

Se for maior ou igual a 18 anos, uma mensagem de sucesso aparece e, após um pequeno atraso, o site abre uma nova aba com o link para o WhatsApp, já com uma mensagem pré-definida.

Isso permite que o usuário continue o processo de cadastro ou atendimento diretamente pelo WhatsApp.
