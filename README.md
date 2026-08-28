# Sistema Lidere — capital de giro e recurso próprio

Controle das operações de capital de giro e do recurso próprio: títulos,
antecipações, prorrogações, razão, resultado por serviço, projeção de caixa e
as parcelas dos contratos com o banco.

**Acesso:** https://leoskatayose-byte.github.io/giro-lidere/

Login por e-mail e senha, com liberação por um administrador. Mesmos usuários
dos outros sistemas da Lidere.

## Privacidade

Coleta apenas o e-mail, para identificar o acesso. Os dados ficam no Brasil
(São Paulo), com acesso restrito a usuários aprovados. Cada pessoa pode baixar
os próprios dados e excluir a própria conta pela tela **Acesso**.

## Como atualizar

O arquivo publicado é gerado a partir do projeto:

```bash
cd "Sistema-Lidere-v2"
python build.py          # gera dist/nuvem/index.html
python testes/smoke.py   # 150+ verificações no navegador
python testes/nuvem.py   # login e RLS contra o Supabase
```

Depois copie `dist/nuvem/index.html` para este repositório e faça `git push`.
Não edite o `index.html` daqui à mão — ele é gerado.
