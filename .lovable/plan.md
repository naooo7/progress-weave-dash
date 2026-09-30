# Desktop navigation sidebar

## Scope
- Add a fixed, compact left sidebar on desktop and laptop widths only.
- Show the Fundamental. brand plus Home, Practice, Progress, and Profile with route-aware active styling.
- Reserve sidebar width so the existing page content shifts right without stretching or changing its internal layout.
- Hide the existing bottom navigation on desktop while leaving it and all mobile layout behavior unchanged.

## Guardrails
- Make the shell change only in the shared screen wrapper.
- Leave Home cards, weekly activity, Continue, Practice, question flows, Results, Progress, Profile, colors, typography, and institution themes unchanged.
- Keep question and Result screens outside the desktop sidebar because they intentionally use focused, navigation-free layouts.

## Validation
- Check Home and another main section at desktop width for reserved space, active states, and intact content sizing.
- Check mobile width to confirm the sidebar is absent and the bottom navigation is unchanged.
