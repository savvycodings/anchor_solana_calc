
<div align="center">

# Autumn School of Solana 2023
</div>

## Task 3
This is your **Task 3** in this course. In the previous tasks, you were introduced to Solana basics, including its architecture, and you also received an introduction to Rust. The goal of this task is to connect these elements and work with Rust on Solana. In this task, you will become familiar with the basic structure of Solana programs and learn how programming on Solana is done.

### Task details
In the previous task, we implemented a calculator, and now we will bring part of this implementation on-chain. The essential idea behind this on-chain program is to initialize a calculator account with the corresponding update authority. The update authority can change operands inside the calculator (X and Y) as well as change the update authority of the Calculator. Additionally, there are methods such as addition, subtraction, multiplication, and division that will perform overflow/underflow resilient operations and emit the result into the Solana logs. Finally, we will subscribe to the logs in our test suite to check the correctness of the results. **Your task is to understand how the program works and implement all parts marked as TODO**.


## Submission Process
As you may not be familiar with the Anchor Project layout, inside `programs/on-chain-calculator/src/lib.rs`, you can find the program logic. Filling in the TODO parts in this file is also your task. Implement the corresponding TODO parts inside `lib.rs`, then test your implementation with the command mentioned below, and when you're done, push the changes of `lib.rs` to GitHub. **Please do not commit any other changes, as it will make the evaluation process more difficult.**

## Deadline
The deadline for this task is **Tuesday, October 10th, at 23:59 UTC**. Note that we will not accept submissions after the deadline.

## Evaluation
We will evaluate your submission using the same test suite provided in this task. Therefore, the requirements for this task are to pass **100%** of the provided tests.

## Setup
For this Task you need:
- [Rust installed](https://www.rust-lang.org/tools/install)
    - Make sure to use stable version:
    ```
    rustup default stable
    ```
- [Solana installed](https://docs.solana.com/cli/install-solana-cli-tools)
    - Use v1.17.0

- [Anchor installed](https://www.anchor-lang.com/docs/installation)
    - Use v0.28.0

### Commands
With the setup I described above, you should be able to run the following commands.

1. You should have **Yarn** installed as it is one of the steps during **Anchor** installation, so once you clone the repo, you should be able to run:
    ```
    yarn install
    ```

2. To build the project, run:
    ```
    anchor build
    ```

3. To test the project, run:
    ```
    anchor test
    ```

If you encounter any questions or issues during the installation process or have any inquiries related to the task, please feel free to initiate a discussion on Discord within the Issues Forum.

## Hints and Useful Links
[Account Context](https://docs.rs/anchor-lang/latest/anchor_lang/derive.Accounts.html)

[Account Model](https://solana.wiki/zh-cn/docs/account-model/)

[Solana Development Course](https://www.soldev.app/course)


-----

## What's next?
If you're interested in our company, don't hesitate to visit our website, [Ackee Blockchain](https://ackeeblockchain.com), or reach out to us on [Discord](https://discord.gg/x7qXXnGCsa). You can also follow us on [X(Twitter)](https://twitter.com/ackeeblockchain?lang=en) for updates.\
For the most recent [Solana News](https://solana.com/news) or [Solana Twitter](https://twitter.com/solana).
