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
