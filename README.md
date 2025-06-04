# Account Project

A simple command-line accounting application written in Java.

## Structure

- `src/account.java` - Main source file containing the CLI logic and account management features.
- `bin/` - Prebuilt class files (`Count.class`, `account.class`).

## Building

The public class inside `src/account.java` is named `account_project`, so the source file should be named `account_project.java` when compiling. After renaming (or adjusting the class name), compile with:

```bash
javac -d bin src/account_project.java
```

Run the compiled program with:

```bash
java -cp bin account_project
```

If you want to run the prebuilt classes included in this repository, execute:

```bash
java -cp bin account
```

## Usage

When you start the program, a menu appears allowing you to enter income, record outlay, view the tree of entries, see ledgers, save to files, free memory, modify entries, set dates and exit. An excerpt from the menu is:

```
┌──────────────────────┐
│  1. 수입 입력         │
│  2. 지출 입력         │
│  3. 수입,지출트리 조회 │
│  4. 장부 보기         │
│  5. 저장 하기         │
│  6. 메모리해제        │
│  7. 수정 하기         │
│  8. 날짜 설정         |
│  9. 종료             │
└──────────────────────┘
```

Select the desired option by entering its number.

## License

This project has no explicit license.
