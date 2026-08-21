# Scoop bucket for AI Limits

[AI Limits](https://github.com/napxlexn/ailimits) is a native Windows 11
floating overlay that shows AI provider usage limits: Claude, OpenAI Codex,
GitHub Copilot, Google Antigravity.

## Install

```powershell
scoop bucket add ailimits https://github.com/napxlexn/scoop-ailimits
scoop install ailimits
```

## Update

```powershell
scoop update ailimits
```

The manifest points at the portable zip attached to every
[release](https://github.com/napxlexn/ailimits/releases); the hash is the
digest GitHub publishes for the asset. A Scoop-installed copy does not
self-update - the app detects a copy it does not manage and leaves updating
to Scoop.
