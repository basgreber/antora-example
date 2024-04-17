# antora-example

Checkout repository and open shell in root directory. Then execute the following commands:

1. `docker run -u root -v .:/antora:Z --rm -it antora/antora ash`
2. `yarn global add asciidoctor-pdf asciidoctor-kroki`
3. `npm i`
4. `antora --fetch antora-playbook.yml`
