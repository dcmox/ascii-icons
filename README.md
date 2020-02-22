# ASCII Icons

ASCII Icons for your Web Components.

## Usage

```html
// in your browser
<script src="./ascii-icons-browser.js"></script>

<style>
	#test:after {
		content: attr(data-content);
		font-size: 40px;
	}
</style>
<div id="test"></div>
<script>
	const el = document.querySelector('#test')
	for (const symbol in AsciiIcon) {
		el.innerHTML +=
			`${symbol}: ` + getAsciiIcon(AsciiIcon[symbol]) + '<br />'
	}
</script>
```

```typescript
const { AsciiIcon, getAsciiIcon } = require('ascii-icons')
const icon = getAsciiIcon(AsciiIcon.Refresh)
```

## Icons

CheckMark: ✓

HeavyCheckMark: ✔

LightCheckMark: 🗸

BallotBoxCheckMark: 🗹

Stop: ∎

Pause: ⏸

FastForward: ⏭

Rewind: ⏮

Record: ⏺

Eject: ⏏

PrintScreen: ⎙

Hamburger: ≡

Network: 🖧

Keyboard: 🖮

Mouse: 🖰

Printer: 🖶

FolderSolid: 🖿

Folder: 🗀

FolderOpen: 🗁

DocumentEmpty: 🗋

Document: 🗎

Page: 🗏

PagesEmpty: 🗍

EmptyCalendar: 🗒

Minimize: 🗕

Maximize: 🗖

FontSizeIncrease: 🗚

FontSizeDecrease: 🗛

Compress: 🗜

Sum: ∑

Bullet: ∙

CubeRoot: ∛

FourthRoot: ∜

Infinity: ∞

Interaction: ∩

Union: ∪

StarSolid: ★

Star: ☆

StarSm: ⋆

TriangleUpSolid: ▲

TriangleRightSolid: ►

TriangleDownSolid: ▼

TriangleLeftSolid: ◀

AscendingSolid: ▴

TriangleRightSmSolid: ▸

DescendingSolid: ▾

TriangleLeftSmSolid: ◂

Ascending: △

TriangleRight: ▷

Descending: ▽

TriangleLeft: ◁

TriangleUpSm: ▵

TriangleRightSm: ▹

TriangleDownSm: ▿

TriangleLeftSm: ◃

Bullseye: ◉

BullseyeAlt: ◎

PieSlice: ◔

PieSliceAlt: ◷

AscendingNode: ☊

DescendingNode: ☋

Telephone: ☎

TelephoneAlt: ☏

Shamrock: ☘

HammerAndPick: ⚒

HammerAndWrench: 🛠

Swords: ⚔

SkullAndBones: ☠

Radioactive: ☢

BioHazard: ☣

YinYang: ☯

SmileyFace: ☺

SmileyFaceAlt: ☻

SunWithRays: ☀

SunWithRaysAlt: ☼

Cloud: ☁

Umbrella: ☂

Recycle: ♻

ChessKing: ♔

ChessQueen: ♕

ChessRook: ♖

ChessBishop: ♗

ChessKnight: ♘

ChessPawn: ♙

ChessKingSolid: ♚

ChessQueenSolid: ♛

ChessRookSolid: ♜

ChessBishopSolid: ♝

ChessKnightSolid: ♞

ChessPawnSolid: ♟

SpadesSolid: ♠

ClubsSolid: ♣

HeartsSolid: ♥

DiamondsSolid: ♦

Heart: ♡

Diamond: ♢

Spades: ♤

Club: ♧

QuarterNote: ♩

EighthNote: ♫

SixteenthNote: ♬

Scales: ⚖

SoccerBall: ⚽

SquaredKey: ⚿

Pick: ⛏

Truck: ⛟

Ferry: ⛴

Scissors: ✂

Airplane: ✈

Mail: ✉

Pencil: ✎

BallotX: ✘

Previous: ❰

PreviousLight: ❮

Next: ❱

NextLight: ❯

ArrowRightAlt: ➔

ArrowRightRounded: ➜

ArrowheadRight: ➤

FeatheredArrowRight: ➳

Timer: ⏱

ThoughtBubble: 💭

Comments: 💬

Copyright: ©

RegisteredTrademark: ®

Refresh: ⟳

RefreshAlt: ↻

RefreshReverse: ↺

ArrowLeft: ←

ArrowUp: ↑

ArrowRight: →

ArrowDown: ↓

Octagon: ⯃

DegreesCelcius: ℃

Phone: 📞

Satellite: 📡

Speaker: 📢

OutboxTray: 📤

InboxTray: 📥

Hammer: 🔨

Baseball: ⚾

Email: 📧

IncomingMail: 📨

LoveLetter: 💌

Present: 🎁

Pushpin: 📌

MailboxEmpty: 📪

MailboxFull: 📫

Memo: 📝

Headphones: 🎧

Paint: 🎨

Magic8Ball: 🎱

Dice: 🎲

OrientalCard: 🎴

Football: 🏈

Volleyball: 🏐

Bomb: 💣

Camera: 📷

Battery: 🔋

SmileyFaceSleeping: 😴

SmileyFaceGrinning: 😁

SmileyFaceTearsOfJoy: 😂

SmileyFaceColdSweat: 😅

SmileyFaceWink: 😉

SmileyFaceSmirk: 😏

SmileyFaceKiss: 😘

SmileyFaceSilly: 😜

SmileyFaceSad: 🙁

SmileyFaceAngry: 😠

SmileyFaceCrying: 😢

SmileyFaceFearful: 😨

SmileyFaceStreamingTears: 😭

SmileyFaceScreamingInFear: 😱

SmileyFaceMedicalMask: 😷

FileFolder: 📁

Globe: 🌐

Watch: ⌚
