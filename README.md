
20 $ в месяц + 10-40 prompts per 5 hours

npm install -g @anthropic-ai/claude-code

пойдет вся настройка + спросит разрешение на доступ к текущей папке

> /init  - Initialize a new CLAUDE.md file with codebase documentation
> /init учти правила в @docs/architecture-rules.md

при инициализации CLAUDE пробежится по проекту создаст структуру и необходимую документацию

CLAUDE.md

> /permissions - все разрешенные команды
> /config - тема, нотификейшены, output, model (Sonnet, Opus, Haiku)

###Добавление в память
1. Project memory ./CLAUDE.md
2. User memory (для всех проектов) ~/ /claude/CLAUDE.md

###Режимы работ
> Thinking mode > /config > Thinking mode: true/false - позволяет лучше решать задачи, но, расходует больше токенов
> shift + tab - показывает
1. Plan mode (сначало делает план - это для детального плана и корректировки + уточняющие вопросы) - после создаст todo list и сделает - после лучше через git status посмотреть изменения
2. Accept
