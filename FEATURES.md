# Built-in features for quality-loop-os

Purpose: software QA testing

1. **organize work and records** — run quality-loop-os-workspace. It creates ~/Documents/quality-loop-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run quality-loop-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/quality-loop-os-session-plans/.
3. **check records and task readiness** — run quality-loop-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/quality-loop-os-workspace features/quality-loop-os-plan features/quality-loop-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for software QA testing:

1. **DB Browser for SQLite** — org.sqlitebrowser.sqlitebrowser
2. **GNOME Builder** — org.gnome.Builder
3. **Wireshark** — org.wireshark.Wireshark

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for software QA testing:

1. **LibreOffice** — create reports and spreadsheets (org.libreoffice.LibreOffice)
2. **Zotero** — manage research sources and citations (org.zotero.Zotero)
3. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
4. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
5. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
6. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
7. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
8. **Foliate** — read EPUB books (com.github.johnfactotum.Foliate)
9. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
10. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
2. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
3. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
4. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
5. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
6. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
7. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
8. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
9. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
10. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
11. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
12. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
13. **Thonny** (org.thonny.Thonny) — write and debug Python code.
14. **Godot Engine** (org.godotengine.Godot) — build and test 2D and 3D games.
15. **OpenSCAD** (org.openscad.OpenSCAD) — model parametric 3D parts in code.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **KDevelop** (org.kde.kdevelop) — edit, navigate, build, and debug software projects.
2. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
3. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
4. **KDiff3** (org.kde.kdiff3) — compare and merge source files and directory trees.
5. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.
6. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
7. **Ark** (org.kde.ark) — open and create common project archive files.
8. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
9. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
10. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
11. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
12. **KGeography** (org.kde.kgeography) — practice country, capital, and map recognition.
13. **Marble** (org.kde.marble) — explore maps and a virtual globe for geographic context.
14. **KStars** (org.kde.kstars) — plan sky observations and explore astronomy simulations.
15. **Clock** (org.kde.kclock) — set study, work, and routine timers with alarms and a stopwatch.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.
