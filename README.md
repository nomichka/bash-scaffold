# bash-scaffold
LLM Bash Scaffolding agent.

**Description**: Runs Buck Shlegeris's and Fabien Roger's Bash Scaffold.

**Purpose**: For Constellation's Astra Fellowship Winter 2022-2023.

**Features**: streaming API, model response comes in token-by-token.

**By**: Naomi Bashkansky

Requires a config.ini file with the following format:

```
[openai]
api_key = sk-c...a
model = gpt-4
```


To run, type the following command: 

`chainlit run bash_scaffold.py -w`

If you want `cd` to work, run with the absolute path instead.
