# Rust no Termux

Módulo do [MPPT24OS](https://github.com/mppt24/MPPT24OS) dedicado à instalação de Rust no Termux, em Android.

## Estado · Em evolução

Os scripts públicos são esboços. Cada um escreve uma mensagem no terminal. A verificação do ambiente e a instalação de Rust ainda estão em preparação.

| Ficheiro | Finalidade prevista |
| --- | --- |
| [`scripts/check.sh`](scripts/check.sh) | Verificação do ambiente Termux |
| [`scripts/install.sh`](scripts/install.sh) | Instalação de Rust |

## Experimentar os esboços

No Termux, abre a pasta do repositório e executa com Bash:

```bash
bash scripts/check.sh
bash scripts/install.sh
```

## Licença

[MIT](LICENSE).
