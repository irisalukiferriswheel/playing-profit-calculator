# Playing Profit Calculator

A bilingual profit and cause-impact calculator for Playing for Good.

## What it calculates

The calculator uses:

- Price paid per player, per game
- Number of players participating per game
- Total games played
- Games won
- Games lost
- Causes supported
- Number of games played for each cause

## 50–50 model

For each game:

```text
Total game pool = price per player × number of players

Player prize pool = total game pool × 50%

Cause share = total game pool × 50%
```

This version assumes one winner receives the entire player prize pool.

## Player results

```text
Total paid = price per game × games played

Prize income = prize per win × games won

Net profit or loss = prize income − total paid
```

## Cause results

```text
Personal contribution to causes =
price per game × games played × 50%

Total generated for causes by all players =
price per game × players × games played × 50%
```

The calculator also provides a breakdown for every cause.

## Validation rules

- Games won + games lost must equal total games played.
- Games assigned to causes must equal total games played.
- Each cause must have a name.
- At least two players must participate per game.

## Languages

The calculator includes an English / Français toggle.

## Technology

- HTML
- CSS
- Vanilla JavaScript
- No backend required
- No database required

## Run locally

Open `index.html`, or run:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Publish with GitHub Pages

1. Create a public GitHub repository.
2. Push the files to `main`.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Choose `main` and `/ (root)`.
6. Save.

## Wix integration

Embed the GitHub Pages URL with a Wix **Embed Site** element.

Recommended initial iframe height: approximately 1100–1300 px, depending on the number of cause rows.
