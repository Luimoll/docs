| C# {% if currentVersion == "free-pro-team@latest" %}| {% octicon "x" aria-label="The X icon" %} | {% octicon "check" aria-label="The check icon" %} | {% octicon "check" aria-label="The check icon" %}<br>`dotnet` CLI | {% octicon "check" aria-label="The check icon" %}<br>`dotnet` CLI | {% octicon "check" aria-label="The check icon" %} | {% octicon "check" aria-label="The check icon" %}<br>`dotnet` CLI |{% elsif currentVersion ver_gt "enterprise-server@2.21" %}| {% octicon "check" aria-label="The check icon" %} | {% octicon "check" aria-label="The check icon" %}<br>`dotnet` CLI | {% octicon "check" aria-label="The check icon" %} | {% octicon "check" aria-label="The check icon" %}<br>`dotnet` CLI |{% elsif currentVersion == "github-ae@latest" %}| {% octicon "check" aria-label="The check icon" %} | {% octicon "check" aria-label="The check icon" %} | {% octicon "check" aria-label="The check icon" %}<br>`dotnet` CLI |{% endif %}