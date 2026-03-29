# 📄 My Resume — Auto-Compiling LaTeX CV

## How It Works

1. Edit `cv.tex` (via GitHub UI, Codespaces, or local push)
2. Push to `main` branch
3. GitHub Actions automatically compiles LaTeX → PDF
4. `Subam_Sarkar_Data_Engineer.pdf` is committed back to the repo

## Quick Edit via GitHub UI

1. Click on `cv.tex` in this repo
2. Click the ✏️ pencil icon (Edit)
3. Make your changes
4. Click **"Commit changes"**
5. Wait ~2 minutes → PDF is updated automatically

## Quick Edit via Copilot

Tag `@copilot` in an issue or PR with instructions like:
> "Update my years of experience to 5+ and add Kafka to technical skills"

## Manual Trigger

Go to **Actions** tab → **Build CV PDF** → **Run workflow** → Click **Run**

## Download Latest PDF

The latest PDF is always available at:
`Subam_Sarkar_Data_Engineer.pdf` in the root of this repo.

Or download from the **Actions** tab → latest run → **Artifacts** section.

## File Structure

```
my-resume/
├── cv.tex                              # ← Edit this
├── Subam_Sarkar_Data_Engineer.pdf      # ← Auto-generated
├── .github/workflows/build-cv.yml      # ← Build pipeline
└── README.md                           # ← This file
```
