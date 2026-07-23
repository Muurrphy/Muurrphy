# Hi, I'm Murphy

I build robots that live in the physical world.

My background is behavioural science — I came to robotics because what I've
always cared about is interaction: what makes something feel alive, safe, and
worth talking to. Now I spend my days building exactly that.

## Currently building

- **A desktop companion robot** — a personality "head" that talks, looks at
  you, and moves: a real-time voice loop (streaming STT → LLM → TTS, ~2s
  end-to-end), muscle-aware lip sync rendered on a chest display, head pose
  that follows the conversation — running across a Mac brain and ESP32-C3
  body over USB. The lip-sync engine is being open-sourced as
  [robot-lipsync](https://github.com/Muurrphy/robot-lipsync).
- **An underwater exploration robot** — early stage, because the ocean is the
  other physical world worth exploring.

## Tools I made for myself and use daily

- [dont-reinvent-the-wheel](https://github.com/Muurrphy/dont-reinvent-the-wheel)
  — a Claude skill that searches before it builds and before it debugs:
  external libraries, my own engineering log, and known dead ends, with an
  explicit reuse / fork / build verdict.
- [ai-roundtable](https://github.com/Muurrphy/ai-roundtable) — a Claude skill
  that runs a grounded, turn-based roundtable between Claude and web ChatGPT
  through the browser, no API keys.

## How I work

I document everything: engineering logs with symptoms, root causes, fixes,
and costs — including the dead ends. Solved problems should become a craft
manual, not vapor. Most of what I know about building I learned by shipping
one robot, breaking it, and writing down why.

