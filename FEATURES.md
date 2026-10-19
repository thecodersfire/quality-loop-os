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
