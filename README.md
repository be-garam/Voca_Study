# Voca_Study
be-garam's Voca(Toefl) Studying Idea base on using Obsidian

## Key Idea
> Obsidian의 property 및 DB 기능을 활용하여 영단어를 쉽게 확인하고 정렬할 수 있는 시스템을 만들고 싶다

### 하나의 Voca가 가진 .md 파일의 모습
```
{
  word: string,
  day: num,
  alias_1: [string],
  meaning_1: string,
  example_1: string,
  alias_2: [string],
  meaning_2: string,
  example_2: string
}  
```
- Need to figure out possibility of putting [Obsidian backlink](https://help.obsidian.md/Plugins/Backlinks) system inside property section
  - Example: example_1: The machine remained [[intact]] despite the explosion
