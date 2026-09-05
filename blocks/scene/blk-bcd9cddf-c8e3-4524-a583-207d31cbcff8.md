Foma projects live on your computer, comprised of almost entirely of human-readable files that belong to you. Connecting Foma to GitHub gives those files a second home: a private, cloud-based **Archive** that holds the complete history of your project and keeps it safe from spilled coffee, dying hard drives, and every other catastrophe the physical world has to offer.

Connecting takes about two minutes, requires no Foma account, and costs nothing. There are two connections to make: sign in to GitHub once on your computer, then link each project you want backed up.

***

### Create a GitHub Account

💬

*NOTE: Already have a GitHub account? Skip ahead to "Sign in from Foma."*

GitHub is a free service that hosts Git-backed projects — millions of writers and programmers trust it with their work every day. (If the word "Git" means nothing to you yet, that is fine. The next section demystifies it.) To register:

1. Visit `github.com/signup` in your browser.

2. Enter your email address, create a strong password, and choose a username.

3. Enter the confirmation code that GitHub emails you.

That is the whole process. GitHub's free plan includes unlimited private repositories, which is everything Foma needs.

💬

*NOTE: Your username is how other writers find you. If you ever use Foma's collaboration features, a co-writer will invite you by your GitHub username — choose one you do not mind sharing.*

***

### Sign in from Foma

Click the GitHub icon in the upper-right corner of the title bar to open the `Archive` menu. Then, click `Sign in with GitHub`.

![image-98.png](assets/image-98.png)

Open the "Archive" menu here

![image-99.png](assets/image-99.png)

Click "Sign in with GitHub" to connect to your Archive

Foma displays a short, one-time code and opens GitHub's authorization page in your browser. (If the page does not open on its own, click `Open GitHub`.)

![image-100.png](assets/image-100.png)

1. Copy the code from Foma — the copy button sits right beside it.

2. Paste the code into the authorization page in your browser.

3. Approve the request when GitHub asks. GitHub names Foma and lists exactly what access it is granting.

The moment you approve, Foma notices on its own — no further clicking required. The `Archive` menu now greets you with your GitHub avatar and username, and you will not need to sign in again on this computer (unless you sign out yourself).

💬

*NOTE: Foma never sees or stores your GitHub password. The one-time code handshake happens directly between you and GitHub, and you can revoke Foma's access at any time from github.com → Settings → Applications.*

***

### Link Your Project to the Archive

The previous step, Signing in, connects *you*. *This* step connects *your project*. With a project open, return to the `Archive` menu — it will report that the project is not linked to a GitHub repository yet. Click `Connect to the Archive`. Foma offers two paths:

**New Repository** — the right choice almost every time. Foma suggests a repository name based on your project folder (rename it if you like), and the repository is set to `Private` by default: nobody on the internet can read your writing but you. Click `Create & Link`, and Foma creates the repository on GitHub and ties your project to it in one motion.

**Existing Repository** — for when you have already prepared a home for this project on GitHub. Foma lists your repositories; pick one, and Foma inspects it before committing to anything. An empty repository gets a clean bill of health. A repository that already has content earns a warning first, because uploading a project alongside unrelated files can cause sync conflicts — click `Link anyway` only if you know what is in there.

💬

*NOTE: Keep writing repositories Private unless you have a very deliberate reason not to. Public means anyone on the internet can read your drafts.*

***

### You're Connected!

From here on, the `Sync to Archive` button — available in both the `Archive` menu and the `Loremaster's Memory` menu — sends your memories to GitHub whenever you choose, and the sync indicators around Foma show you at a glance what has and has not been backed up yet. The rest of this chapter walks you through that workflow.

Signing in also unlocks Foma's collaboration features: invite a co-writer with `/share`, or read and annotate your manuscript on your phone with the Foma Reader companion app. Both ride on the same GitHub connection you just made.

Try this: connect this very demo project to your Archive. It is a disposable copy, which makes it the perfect place to rehearse before you connect a project you care about.

When you are connected, continue to the next section to learn about the machinery underneath: Git, snapshots, and the "time machine" that your writing now lives in.
