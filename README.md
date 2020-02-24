# Jesse's Anti-Procrastination Script

Tired of procrastinating? `procrast` is here to help!

This script blocks websites by adding a bogus entry to `/etc/hosts`. You can then toggle "procrastination mode" on and off.

- Use `procrast add` to add a site to the procrastination list
- Use `procrast remove` to remove a site from the procrastination list
- Use `procrast no` to **stop** procrastinating
- Use `procrast yes` to start procrastinating

## Examples

You probably want to add both `www.site.com` and `site.com`.

If you wanted to block YouTube, you'd do...

```console
procrast add youtube.com
procrast add www.youtube.com
```

Then `procrast no` will block YouTube and `procrast yes` will unblock YouTube. You never have to add YouTube to the procrastination list again.

## Note on Facebook

If a site includes Facebook's tracking JavaScript, blocking Facebook might cause that site to not load (or load slowly). Keep that in mind if you find a site being suddenly slow to load.
