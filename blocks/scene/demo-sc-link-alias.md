### Creating Actants

*Actants* can be created in four ways.

1. Click on the `+` next to the word "Worldbuilding" in the Worldbuilding domain to create a top-level *Actant*. If you create a new Novel or Game project, a few top-level *Actants* are created for you by default, such as Characters and Locations. Top-level *Actants* generally exist as sorting containers.

![image-110.png](assets/image-110.png)

Create a top-level Actant here

2. Click the `+` next to an *Actant* in the side bar to create a nested *Actant* under that *Actant*. Right-click on the `+` button to set the default *Actant* class for all child *Actants*. For example, if you have a top-level *Actant* named Characters, you can right-click on the `+` next to Characters to set its default to automatically create nested Characters.

![image-111.png](assets/image-111.png)

Nest a new actant underneath its parent

3. Type `@` in any editor surface to create a new *Actant* in-line or link a word to an existing *Actant*. To create a new *Actant*, follow `@` by typing the name of the *Actant* that you're creating, then hit `Enter` or click "Create `<name>`", then select the *Actant* class. Once you've selected a class, you'll be asked whether you want to auto-link the *Actant*. If you select "yes", every time you type the name of the *Actant*, the link will be created automatically.

![image-112.png](assets/image-112.png)

Create a new Actant in-line by pressing @ followed by the desired Actant name

4. Highlight a name with the cursor. A formatting bar will appear above the highlighted text. Click the "Link or create Actant" button to complete the action.

![image-114.png](assets/image-114.png)

### Retroactively link an Actant to all existing instances in the project

You may find that you want to create links to *Actants&#x20;*&#x61;fter you've written several chapters during which the name appears hundreds or thousands of times throughout the project. Foma makes it easy to link all instances of a name to its backing *Actant&#x20;*&#x62;lock. There are two main ways to do so:

1. Highlight the Actant's name anywhere in the text. Click "Link or create Actant". Then, if the Actant's Worldbuilding entry already exists, click the scope for which you would like to link the name. If you would like to link all instances of the name in the project, click `All in Project` .

![image-117.png](assets/image-117.png)

2. Link all instances to all Actants in the project from the Auto-linked Actants management menu from Editor Settings.

![image-118.png](assets/image-118.png)

From the Auto-linked Actants menu, click "Link Everything" to link all *Actants&#x20;*&#x61;nd their *aliases&#x20;*&#x74;hroughout the project.

![image-119.png](assets/image-119.png)

### Auto-linking

*Actants&#x20;*&#x63;an be configured to automatically link to its name in the text anywhere when that name is written. For example, the name `John Doe` is already configured to automatically link when the name is written. If you type "John" in this project, the name will perform a gentle bounce animation to indicate that it has been linked to the `John Doe` character page.

The most convenient, accessible way to auto-link a word to its *Actant&#x20;*&#x70;age is to type `@` + the name. If the Actant already exists, it will filter to the top of the list of Actants in the popup menu.

![image-115.png](assets/image-115.png)

John Doe filters to the top

Select the Actant by pressing `Enter` while the name is highlighted or click on the name in the popup menu. Once the Actant's name is selected, a prompt will appear asking if you would like to auto-link to the Actant.

![image-116.png](assets/image-116.png)

Hit "Enter" or click "Yes" to auto-link

Once the auto-link has been established, simply typing the name or any of the name's aliases will link to the *Actant&#x20;*&#x62;lock in Worldbuilding.

### Removing an Actant link

As you're typing, you may find that you need to edit or click into an *Actant's&#x20;*&#x6E;ame without navigating to its backing *Actant&#x20;*&#x62;lock in Worldbuilding. There are two ways to remove an *Actant&#x20;*&#x6C;ink inside the editor.

1. Place the caret after the linked *Actant's&#x20;*&#x6E;ame and press `Backspace`. Before deleting a character in the name, the first `Backspace` will remove the *Actant&#x20;*&#x6C;ink and subsequent keystrokes will delete characters in the name.

2. Hover the cursor over the linked Actant's name. The cursor should be a pointer. Then, press and hold `Ctrl` (`Command` on Mac), the cursor should change from a pointer to an insertion caret. While the cursor is an insertion caret, click anywhere in the *Actant's&#x20;*&#x6E;ame. This will remove the Actant link, making the text editable.

### Aliases

Many *Actants* may be referred to by nicknames, abbreviations, or monikers. Foma manages *Actants&#x20;*&#x74;hat have multiple names using *aliases*. Assign *aliases&#x20;*&#x74;o your *Actants* by typing `/autolinks` or clicking the Settings cog icon in the upper-right of the title bar and navigating to `Editor `→ `Manage actants`.

The `Manage actants` menu allows you to establish any number of aliases for your *Actants* so that an *Actant* named "Professor Gregory" will also generate auto-links for "Prof. Gregory", "Gregory", or "Greg" too.

💬

NOTE: from the `Manage actants` menu, click "Link everything" to establish links between every *Actant* and/or alias that exists in Worldbuilding across all domains.

### Tips

Re-organize child *Actants* by dragging the *Actant* by its drag handle in the Worldbuilding side bar.

💬

*Note: You can reparent Actants in this way as well.&#xA0;*

💬

*Note: if you need to click on an Actant as text without navigating to its Actant page, you can hold&#x20;*`Ctrl`*&#xA0;and click on the Actant's name. This breaks the link to the Actant and places the caret inside of the word so that you can edit the text.*

Alias Examples:

John met Jane at the coffee shop again. The umbrella stayed home this time.

***

### Activity

Try this: type `/autolinks` to open Auto-link Actants. Add "JD" as a link word for John Doe, then type JD on a new line below and watch it turn into a link.
