# BuildIT v2 — Concept

## Positioning line
**"I'm flipping my life around through BuildIT."**
Supporting line: *A turnaround, built in public. Every website is proof.*

BuildIT is not "a teen who makes websites". It is a young founder's turnaround, happening in real time, and every site he ships is a receipt. Visitors don't buy pity; they buy evidence. So the page moves from a single honest admission, to the values he now lives by, to the proof (real, live projects), to the way he gives back, to a simple deal that lets you be part of the story.

## Narrative arc (chapters)
| # | Chapter | Job it does |
|---|---------|-------------|
| 00 | **The Flip** (intro) | Kinetic letters: "I'm flipping my life around through BuildIT." "flipping" literally flips. Stops the scroll. |
| 01 | **Hero — Built in public** | Who, what, one CTA. "A turnaround, built in public." Sticky "Start a project" always visible. |
| 02 | **Then** | His own words, revealed word-by-word as you scroll: "Not long ago I was with the wrong crowd…". Honest, short, no detail. |
| 03 | **The Flip — values** | Honesty · Owning it · Showing up · Giving back · Earning trust. Giant editorial type, each line lights up as it enters. |
| 04 | **Proof — the reel** | Horizontal case-study reel of 4 live projects with real screenshots in browser + phone frames. |
| 05 | **Giving back** | "I took from a community once. Now I build for it." Charities & community groups: always free. |
| 06 | **The deal** | First 5 websites free for an honest review: five slots, each "open". Any domain extension. Hosting is a footnote. Review wall = clearly-marked placeholders. |
| 07 | **What's next** | "What I want to achieve" — placeholder for Tomas's own words. |
| 08 | **Start** | Phone, email, project brief. Footer with Ampyre line. |

## Storyboard (section by section)
- **00 Intro**: full-screen ink. Each letter drops from above with squash-and-stretch bounce, staggered; "flipping" letters rotate 180° → upright; "BuildIT." lands last in electric cyan. A mono counter ticks 000→100 bottom-left. Then 6 vertical strips lift away to reveal the hero. Skip button (focusable, Esc works). Once per session (sessionStorage). Reduced motion: simple fade of the full line. Clicking the logo = full reset: scroll to top, clear state, replay.
- **01 Hero**: huge two-line headline, small "Chapter 01" mono label, short sub, 2 buttons (Start a project / Watch the proof). Small illustrated Tomas character tucked in the corner (≤160px), secondary. Gradient light blob slowly drifts behind (Lusion/Dogstudio vibe), film grain over everything.
- **02 Then**: a single quote, ~5vw serif italic, words go from 15% to 100% opacity as scroll progresses (Lando Norris / Apple-style scrub).
- **03 Values**: five giant words stacked; the active one fills cyan and shows a one-line meaning in Tomas's voice (placeholder marked where he should rewrite).
- **04 Proof**: section pins; vertical scroll drives a horizontal track of project cards (desktop). Each card: big screenshot in browser chrome, phone shot overlapping, name, what the project is, "Visit live site ↗". Mobile: native swipe with snap. Phrased as "projects", never "built solely by".
- **05 Giving back**: split-screen statement + "Always free for charities & community groups" stamp.
- **06 Deal**: 5 numbered slots (01–05) styled like tickets; review wall with dashed placeholder cards "[Placeholder — real review goes here once client 01 signs off]".
- **07 Next**: "What I want to achieve" — dashed placeholder block.
- **08 Contact**: giant tap-to-call number, email, brief link. Footer muted.

## Visual direction
- **Type**: *Bricolage Grotesque* (display, 800, tight tracking) for kinetic/editorial headlines; *Instrument Serif* italic for his own words (the human voice); *JetBrains Mono* for chapter labels / counters (the "builder" voice).
- **Palette**: Ink `#0E0E0C`, Bone `#F2EDE3`, Electric cyan `#22D3EE` (the flip, sampled from the BuildIT logo; ink text on cyan 10.3:1), Muted `#A39E93` (AA on ink: 7.3:1), Sky `#8FB8FF` for tiny details. Cyan on ink 10.7:1. Background light: deep blue-black glow (#1E40AF / #082F49). No pink or purple anywhere; logo gradient re-tinted cyan→sky→blue.
- **Motion**: bounce/squash letters, scroll-scrubbed word reveal, pinned horizontal reel, magnetic buttons, blend-mode cursor ring (pointer devices only), strip-wipe transitions. All disabled or reduced under `prefers-reduced-motion`.
- **Texture**: SVG film grain + soft drifting gradient light.

## Inspiration mapping
| Technique | Inspired by |
|---|---|
| Bouncing, squash-and-stretch kinetic intro letters | Don't Board Me, Resn, Pangram Pangram |
| Mono 000→100 counter during intro | Locomotive, Obys, Active Theory |
| Strip/curtain wipe from intro into hero | 14islands, Immersive Garden, Permian |
| Big bold editorial type + scroll-scrubbed reveal | Lando Norris (OFF+BRAND) |
| Drifting gradient light + grain | Lusion, Dogstudio |
| Horizontal pinned case-study reel | Immersive Garden, Locomotive |
| Magnetic buttons + blend cursor | Cuberto |
| Blueprint grid / "built" aesthetic in labels | Basement Studio |
| Logo = "start" / replay the world | Bruno Simon |

## Why it wins attention and clients
1. The first five seconds are a sentence nobody expects from a web studio — it's a promise, not a pitch.
2. The story is carried by **his own words**, so it reads as honest, not engineered.
3. Proof arrives fast: four live projects with real screenshots, no invented claims.
4. The offer turns sympathy into action: you can *be* one of the five, or back a charity build.
5. Award-level craft (kinetic type, pinned reel, grain, cursor) is itself the portfolio piece.
