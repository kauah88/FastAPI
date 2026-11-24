# Como criar um ambiente virtual

1. Crie uma pasta para o projeto.
2. Abra essa pasta em um terminal.
3. Execute o comando abaixo para criar o ambiente virtual:

   ```powershell
   python -m venv .venv
   ```

   > `.venv` é o nome do ambiente virtual e pode ser alterado.

4. Copie o caminho relativo do arquivo `Activate.ps1` ou use o comando:

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

Após a ativação, o ambiente virtual estará pronto para uso.