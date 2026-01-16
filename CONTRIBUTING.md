# Contributing to CodeShittifier

So you want to make code even worse? Excellent. Here's how.

## Ground Rules

1. **Be nice to people** - We're making code terrible, not making people feel terrible
2. **Keep it compiling** - Code should still compile after shittification
3. **Have fun** - If you're not laughing while breaking code formatting, you're doing it wrong

## How to Contribute

### Got an idea?
Open an issue. Tell us how to make code even more unreadable.

Good ideas:
- New chaos strategies
- Better randomization
- Language-specific nightmares
- Performance improvements (yes, really)

Bad ideas:
- Actually breaking code
- Making it genuinely malicious
- Being a jerk

### Want to code?

1. Fork this repo
2. Create a branch: `git checkout -b feature/more-chaos`
3. Make your changes
4. Test it: `javac CodeShittifier.java && java CodeShittifier --dry-run examples/`
5. Make sure it still compiles the shittified code
6. Commit: `git commit -m "Add random whitespace chaos"`
7. Push: `git push origin feature/more-chaos`
8. Open a Pull Request

### Testing Your Changes

Minimum testing checklist:
- [ ] Code compiles
- [ ] Shittified code still compiles
- [ ] Dry-run mode works
- [ ] Backup creation works
- [ ] Doesn't crash on empty files

Test it on some real Java/Kotlin files. If the output makes you uncomfortable, you're on the right track.

## Code Style

Ironic, isn't it? But yes, keep the CodeShittifier code itself clean and readable. 

- Use clear variable names
- Comment the tricky bits
- Keep methods under 50 lines
- Follow standard Java conventions

We're making OTHER people's code terrible, not our own.

## Ideas We're Considering

Want to work on something? Pick from these:

**Easy:**
- Add more operator chaos patterns
- Better randomization algorithms
- More example files
- Documentation improvements

**Medium:**
- Support for .groovy or .scala files
- Shittification profiles (Enterprise Java, Startup Kotlin, etc.)
- Config file support
- Better CLI output

**Hard:**
- Gradle plugin
- IntelliJ/Android Studio plugin
- Maven plugin
- Web playground

**Memes:**
- Random code comments ("// TODO: Why?")
- Emoji in variable names (still valid Java!)
- Random Unicode whitespace
- Unnecessarily complex boolean logic

## What We Won't Accept

- Code that breaks compilation
- Malicious features (deleting files, etc.)
- Changes that make the tool less fun
- Removing safety features (backups, dry-run, etc.)
- Being mean to contributors

## Questions?

Open an issue. Or just wing it. We're making a tool that ruins code formatting, let's not take this too seriously.

## The Fine Print

By contributing, you agree that:
- Your code is yours to contribute
- You're okay with the MIT license
- You understand this is a parody/educational tool
- You won't sue us if someone actually uses this in production (please don't)

---

**Thanks for making the world's code a little bit worse!** 💩

Remember: Good code is temporary. Shitty code is forever (until someone runs a formatter on it).
