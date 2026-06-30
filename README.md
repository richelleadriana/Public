# Public

I installed these tools: Cursor, Git Bash, Claude Code extension, Codex extension  
  
The Steps I completed:  
    1. Install Cursor IDE  
    2. Sign up for Cursor  
    3. In Cursor, go to File -> Open Editor Window  
    4. In Cursor, go to View -> Extensions.  
    5. Seach for Claude Code and install the extension, and log into it.  
    6. Search for Codex and install the extension, and log into it.  
    7. Go to browser and open [https://github.com/](https://github.com/) to create an account  
    8. Create a new repository in Github, name it, make it public and enable the 'Add README' toggle.  
    9.Go back to Cursor -> open the Primary Side Bar.  
    10. Click the 'Changes' icon and follow instruction to install Git Bash.  
    11. Once installed, open Cursor again to find the 'Clone repo' option now available.  
    12. Go to the public git hub repository that was made earlier and copy the HTTPS code link.  
    13.In Cursor, click the 'Clone repo' option and paste the HTTPS code link of the git hub repository.  
    14. Find the README.md file on the sidebar and click to open and write.  
    15. Write all the tools installed, steps completed, and issues encountered.  
    16. Check the sidebar's Changes tab and click to Commit the changes into Github.  
    17. Copy the [README.md](http://README.md) file link in github.



Issues I ran int and how I solved them:

1. Unable to find Extensions option in Cursor: I googled the issue and found a solution, which is to access the Open Editor Window in File. After clicking that, I can find the Extensions and install the needed ones.
2. I didn't know how to open the Github repo in Cursor so I googled this issue, turns out I need to clone them. But to Clone them, I need to have Git Bash installed. I installed it and was able to finally see the clone option.
3. There was an issue with Committing the changes into Github, an error appeared. I googled the issue and found that to fix the missing identity error in Git, I need to run the global config commands in the terminal to tell Git who I am. After running this, I was able to commit the changes int Github.  

# AI SEO Research Repository

## How Data Was Collected
I used **Codex** to automate the process for both Youtube transcripts and Linkedin posts:

### 1. LinkedIn Research Process
1. I manually copied the raw, unformatted post text directly from the creators' Linkedin  recent content page.
2. I fed this raw text into Codex and told it to clean up the messy social media spacing, remove extra emoji clutter, and organize multiple posts using clean headers.
3. Codex saved the polished text into individual Markdown files inside my `research/linkedin-posts/` directory, naming each file after the expert.
### 2. Youtube Transcript Process
1. Here, Codex fetched raw transcripts using the `supadata.ai` API. I signed up and got a free key.
2. Codex then cleaned up raw JSON data into clean plain text, removing timestamps.
3. Codex automatically saved the output into individual .md files inside `research/youtube-transcripts/` using the video names as the file titles.
4. Codex also included the original YouTube source link at the top of every file for traceability.

---

## Why I Chose Each Expert

I chose these 10 individuals because they are real-world practitioners who share actual data and case studies rather than theories:

1. **Jake Ward** – I chose him because he shares  blueprints on scaling thousands of high-traffic pages using AI templates.
2. **Eli Schwartz** – I chose him because of his enterprise consulting background, which provides  insights on how to make AI content satisfy human intent rather than just keywords.
3. **Kevin Indig** – I chose him because he specializes in enterprise SaaS growth and offers practical frameworks for integrating AI search optimization (GEO) into existing platforms.
4. **Bernard Huang** – I chose him because, as the founder of Clearscope, he reveals exactly how to build content that matches modern AI semantic layers.
5. **Lily Ray** – I chose her because she closely monitors Google's algorithmic changes and tracks how to configure AI generation tools to maintain quality.
6. **Aleyda Solis** – I chose her because she provides technical, step-by-step blueprints on how to use content spaces for global, multi-lingual AI search layouts.
7. **Matt Diggity** – I chose him because he runs split-tests comparing pure AI, hybrid, and human text, giving access to traffic retention and indexing data.
8. **Craig Campbell** – I chose him because he breaks down the raw operational setups for high-volume content, focusing heavily on bulk automation tools and scraping workflows.
9. **Marie Haynes** – I chose her because she maps out how search engines are evolving into semantic answer engines, helping me configure AI tools to align with modern algorithmic trust layers.
10. **Ryan Law** – I chose him because his work at Ahrefs shows teams how to use LLMs as high-speed analytical writing assistants while keeping human creative direction in control.