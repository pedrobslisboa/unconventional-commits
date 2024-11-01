# Unconventional Commit Messages

Because being conventional is boring!

See how a minor change to your commit message style can make a difference. [Examples](#examples)

## Commit Formats

### Default

<pre>
<b><a href="#types">&lt;optional intro&gt;</a> - </b><b><a href="#types">&lt;optional type&gt;</a></b></font>(<b><a href="#scopes">&lt;optional scope&gt;</a></b>): <b><a href="#subject">&lt;optional subject&gt;</a></b>
<sub>empty separator line</sub>
<b><a href="#body">&lt;optional body&gt;</a></b>
<sub>empty separator line</sub>
<b><a href="#footer">&lt;optional footer&gt;</a></b>
</pre>

Everything is optional, YEY!!!! So then you can do whatever you want without barriers.

### Intro

Because every good writer writes a nice intro.
You can start with the most common way: once upon a time.

Here are some tips to let your mind fly:

- Start with action or dialogue.
- Ask a question or set of questions.
- Describe the setting so readers can imagine it.
- Give background information that will interest readers.
- Introduce yourself to readers in a surprising way.

### Types

- `feat?` Does this commit add a new feature? You will never know. It could fix a bug.
- `unfix` Commit that provides a bug to the code, then you can fix it later. We add bugs constantly, so why not be precise when adding them?
  It would be best if you keep your job; the best way is always to have something to fix.
- `refactor!` Commit that rewrites or restructures your code, and it doesn't change any behavior; however, it does a breaking change on the versioning.
- `wip` Let's turn this common commit into our rules, and why not have it on a changelog too? Can you imagine? We are in the future, baby.
  Ex:

```
# Change Log

All notable changes to this project will be documented in this file.
See [Unconventional Commits](https://unconventionalcommits.org) for commit guidelines.

### [0.2.124](https://github.com/your-workspace/your-library/compare/@your-workspace/your-library@0.2.123...@your-workspace/your-library@0.2.124) (2023-01-10)

### Work in progress

- I DON'T WANT TO LOSE IT ([1234567](https://github.com/your-workspace/your-library/compare/@your-workspace/your-library/commit/2915810e57bb222bad8e24d1fa9daf1554e15ac0))
- TESTE ([1234567](https://github.com/your-workspace/your-library/compare/@your-workspace/your-library/commit/2915810e57bb222bad8e24d1fa9daf1554e15ac0))
- TESTE 2 ([1234567](https://github.com/your-workspace/your-library/compare/@your-workspace/your-library/commit/2915810e57bb222bad8e24d1fa9daf1554e15ac0))

```

- `test` Commits something that you want to test. It does not add test files; it only informs that something is being tested.
  Ex: You want to test something on staging or even in production (YEAAAAH do it, why not?), how do you provide info that the code a test? With the `test` type!
- `<any emoji you want>` Because a picture is worth a thousand words.

### Scopes

Nobody cares, NEXT!

### Subject

The `subject` is supposed to contain a succinct description of the change. But do you really care about it? We are suggesting a better way to deal with it.

- Is **optional** part of the format, as everything.
- Use the imperative(**BORING**), declarative, exclamatory and interrogative on the past, future, or present(**BORING**) tense. You should be able to express yourself, don't limit your imagination on what kind of sentence you should create.
  - e.g., `tests are good`, `Am I happy with this change?` and `Oh, that is an excellent bug to fix!`.
- Don't capitalize only the first letter; capitalize ALL LETTERS, BECAUSE YOU NEED TO BE CLEAR!!!!!
  - e.g., `TESTS ARE GOOD`.
- No dot (.) at the end; are you an animal? Use `;` even on interrogative sentense.
- Have I said you can use emojis here? Yeah!!!
  - Think of `🔧 the 🐛` = `Fix the bug` :3 Gorgeous.

### Body

The `body` should include the motivation for the change and contrast this with previous behavior. Should, not **must**... should!

- Is an **optional** part of the format, as everything.
- Use the imperative(**BORING**), declarative, exclamatory, and interrogative on the past, future, or present(**BORING**) tense. You should be able to express yourself, don't limit your imagination on what kind of sentence you should create. Use "changed", "changes", "change", and the greatest one: "changing".
  - e.g., `I'm changing the behavior of the X component`.
- This is the place to mention issue identifiers and their relations, talk about your emotions and send a message to your lover :heart:.

### Footer

This is one of the most powerful features because you can define here if this commit is a BREAKING CHANGE with a message; nice, right? But you can also provide the type to overwrite the previous type set!!!

- Is an **optional** part of the format, as everything.

Ex:

```
wip: SAVING FOR LATER;


FEAT?: is it a feature or a WIP? .-.
```

The output is going to be:

```
# Change Log

All notable changes to this project will be documented in this file.
See [Unconventional Commits](https://unconventionalcommits.org) for commit guidelines.

### [0.2.124](https://github.com/your-workspace/your-library/compare/@your-workspace/your-library@0.2.123...@your-workspace/your-library@0.2.124) (2023-01-10)

### Is it a feature?

- SAVING FOR LATER ([1234567](https://github.com/your-workspace/your-library/compare/@your-workspace/your-library/commit/2915810e57bb222bad8e24d1fa9daf1554e15ac0))
```

### Examples

- ```
  feat?(button);
  ```
- ```
  unfix: REMOVE THE PROP CHILDREN ON TYPOGRAPHY;
  ```
- ```
  refactor!(✨);
  ```
- ```
  wip: TESTEEEEEE;
  ```
- ```
  refactor!: I'M CHANGING THE WAY WE HANDLE ONCHANGE;
  ```
- ```
  Hello, my name is Pedro, and that is my commit - feat?: REMOVE EMPTY LINE;
  ```
- ```
  unfix: ADD onClick HANDLER TO <div/> AT TEXT COMPONENT;

  WIP: this is a bug in progress.
  ```

- ```
  unfix: ADD onClick HANDLER TO <div/> AT TEXT COMPONENT;

  WIP: this is a bug in progress.
  ```

- ```
  test: VALIDATE IF IT BREAKS THE LOGIN ON PRODUCTION;

  I'm testing the new way to log in to the website.
  Lívia, I LOVE YOU!!!!
  ```

- ```
  Once upon a time - feat?: INIT;
  ```
