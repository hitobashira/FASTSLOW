# FASTSLOW 🦀 meets 🐫!

## Overview
Sudden mid-term recap! 🦀 (Rust) meets 🐫 (Perl) birthed **FASTSLOW The FLOW**—a dynamic tool that blasts through files with parallel processing. Inspired by the ostrich (🦤), it was nearly named OST or ostrich.

- Like mom's special soup—kindness baked in! It gently bans non-UTF-8 encodings. SHIFT_JIS? What’s that, tasty?!
- Honors the beauty of tools like fd and parallel, inheriting their variable placement for a super-subset vibe.
- Makes PCRE (Perl code) easier! `--rawperl` lets Perl 🐫 shine.
- WSL2 breaks Windows limits! ❤ Cross-build can’t bridge the gap—challenges welcome!

## Slogan
**FASTSLOW breaks boring routines**  
- Turns dull days fun. Minimal Linux learning needed!

## WSL Catchphrase
**"Run it on WSL, and enter a world where the impossible thrives—this paradoxical WSL realm welcomes you! ❤"**  
- English: **"Welcome to the Paradoxical WSL World Where the Impossible Comes Alive! ❤"**  
- Note: "Panic Room" style—unlock new possibilities with WSL! (WSL2 testing in progress, community feedback welcome)

## Features
- **Parallel Processing**: Default `--jobs = num_cpus * 0.8` (16→13, 8→6, 4→3) for safe speed.
- **Subcommand bbr**: Easy mode! 10% less memory, progress [=>] 75%.
- **Support**: Linux/WSL2 only. Deliberately no Windows native.

## Installation
Under development! Planned Rust build. Details later.

## Usage
### Sample Commands
- Basic: `fastslow --jobs 22 --progress mv {} output/ ::: *.jpg`
- Easy Mode: `fastslow bbr mv {} output/ ::: *.jpg`
- Advanced: `fastslow bbr convert {} -resize 50% {}.thumb ::: *.png` (ImageMagick)

### Notes
- Ditch the mouse—activate your brain with CLI! 2025 is the year of CLI.
- WSL2 testing? I’m too busy—rely on the community for feedback!

## Development Status
Prototyping now. Contributions and tests welcome!

## License
TBD. Specs are still up in the air.

## Development Tale (Play Format)
More fun than coding or using—our story is coming soon!

---

🦤
