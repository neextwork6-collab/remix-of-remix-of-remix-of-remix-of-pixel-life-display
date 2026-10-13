<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Preserve the TanStack bootstrap and pinned dependencies when importing content pages; source package scripts are not executed.
- Keep imported binary media as Lovable asset pointers and resolve them through shared media helpers so the full source imagery remains available without repository binaries.
- Render news/event photo branding through BrandedPhoto for both thumbnails and image viewers so logo fitting and stacking stay consistent.
- Keep About presentation overrides in a shared browser-safe module and scope layout adjustments to About pages, so imported source content and other pages remain unchanged.
- Keep support-page copy and presentation overrides in a browser-safe support module, leaving the imported source archive intact.
- Store generated narration as a shared media pointer and replay it with native audio controls; playback must not generate another recording.
- Contact and joining enquiries prepare email drafts with explicit status messages, rather than claiming unsent forms have been delivered.
