# Accessibility

> A web version of this statement also lives at [isaacadjei.me/accessibility](https://isaacadjei.me/accessibility).

This is my accessibility statement, kept in one place so my website and every repository can point to it. It covers what I do so that my work can be read and used by as many people as possible, where the gaps are and how to tell me when something gets in the way.

## What I aim for

- Content that reads in order under real headings, so a screen reader and the page outline can move through it.
- Everything reachable from the keyboard, with a visible focus.
- Text that stands on its own: link text says where a link goes, images carry alt text and colour never carries a meaning alone.
- Respect for system settings: a light or dark theme, reduced motion and your own font size.
- Plain language, with a term explained where it first appears.

## My website

[isaacadjei.me](https://isaacadjei.me) has these in place:

- The page language is declared and every page has one heading outline.
- A "Skip to content" link is the first thing the keyboard reaches on every page.
- The theme follows the system setting, with a toggle in the header.
- Animation in the header, the favicon and the typing motto stops when the system asks for reduced motion.
- Icon-only buttons carry a label for screen readers.
- The command menu (Ctrl or Cmd with I) reaches every page from the keyboard. The All Pages page lists them all in plain text.
- Images carry alt text. Code, commands and output are shown as text, never as screenshots.

### Known limitations

> [!WARNING]
> The charts, maps and 3D views on the lab and stats pages are visual by nature. Where a chart has a text summary the figures are in it, but not every chart has one yet. Where a page embeds content from another service, that content follows the service's own accessibility.

## My repositories

Documentation in every repository follows the same rules:

- a real heading outline, so screen readers and the page outline can jump between sections
- link text that says where the link goes, never "click here"
- alt text on images and badges
- diagrams written as Mermaid or tables where possible, so their content is text
- code, commands and output as text, never as screenshots
- callouts that carry a label such as Note, Tip or Warning, never colour alone
- plain language, with a term explained where it first appears

A repository whose contents change how something looks, sounds or is operated, such as my dotfiles and editor configurations, documents its own settings in its own `ACCESSIBILITY.md`: the colours and contrast, the key bindings, the motion and what to change for a different need. That file takes precedence over this one.

> [!NOTE]
> Many of those settings are preferences rather than requirements. Change them freely in your own copy. If a change would help other people too, open an issue or a pull request on that repository so I can consider it for everyone.

Repositories with their own statement: [dotfiles](https://github.com/zaccesss/dotfiles), [terminal-config](https://github.com/zaccesss/terminal-config), [vscode-config](https://github.com/zaccesss/vscode-config), [neovim-config](https://github.com/zaccesss/neovim-config), [tmux-config](https://github.com/zaccesss/tmux-config), [cli-tools-config](https://github.com/zaccesss/cli-tools-config), [jetbrains-config](https://github.com/zaccesss/jetbrains-config), [raycast-config](https://github.com/zaccesss/raycast-config) and [rectangle-config](https://github.com/zaccesss/rectangle-config).

## Reporting a barrier

If anything on the website or in a repository is hard to read or use, tell me. For a repository, open an issue there. For the website, use [my contact page](https://isaacadjei.me/contact) or email contact@isaacadjei.me. Say what you were trying to do, what happened and what would have worked better. If the assistive technology or the settings you use are relevant, mention them too.

> [!IMPORTANT]
> I treat an accessibility problem as a bug, not a feature request. These are personal projects, so I am not always quick, but a barrier goes to the front of the queue.

## Where this applies

This is the shared statement for [my website](https://isaacadjei.me) and most of [my projects](https://isaacadjei.me/projects). A repository with its own `ACCESSIBILITY.md` takes precedence over this one.

---

<div align="center">
Made with care by <a href="https://isaacadjei.me">Isaac Adjei</a>
</div>
