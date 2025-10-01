# Gemini Project Instructions

## Core Conventions

- 마크다운 형식을 사용하돼 모든 표기 다 보여줘
- 코드를 보여줄 때는 줄번호는 사용하지마
예를 들어, 이런식으로  
```
  db.users.insertMany([
        { name: "Jane Smith", age: 25, email: "jane.smith@example.com", status: "active" },
        { name: "Peter Jones", age: 42, email: "peter.jones@example.com", status: "inactive" }
      ])
```

- 컨텐츠 설명에 존댓말 쓰지마 그 대신 실버 불릿 형식으로 정리해줘
예를 들어,  모든 문장을 이런 식으로 정리해줘
```
db.collection.deleteOne({ <filter> })`**: 조건(`filter`)에 맞는 **첫 번째 하나**의 도큐먼트를 삭제.
**주의**: `{}`를 조건으로 주면 컬렉션의 모든 도큐먼트가 삭제되므로 신중하게 사용해야 함
```
