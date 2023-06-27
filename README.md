# Tell me why (ain't nothing but a project management tool)

[SLIDE1]: Cover and title of the talk "Taiga: Tell me why (ain't nothing but a project management tool)"

Do you know what? We should change the topic completely. Let's talk about the renovation of my house instead. Let's take those 24 minutes from these good people and tell them everything about the faucets that I have to change, the switches, the tiles... I don't know which wall the shower should be on... I think it would be a better use of everybody's time.  Don't you think?
If anybody in the audience has something to say about it, they can text me at this number.

[SLIDE2]: Phone number but without enough contrast and blurry enough so nobody can read it.

Well, it looks like nobody is objecting. Everybody agrees, so let's start.

[SLIDE3]: Plan of a house. One wall is highlighted to be demolished.

This is the plan of my house and as you can see, we are going to start demolishing this wall, the fourth wall.

[SLIDE4]: Illustration of an owl in the forest over a big title that says "Plot Twist".

We wouldn't do that to you! It felt weird, didn't it? Having something to say and not being able to, not because it was not up to you to decide, but simply because you don't have access to the place where decisions are being made.

Well, this is what we intend to avoid in Taiga Next. We think that a tool that is meant for making decisions shouldn't leave anybody behind.

[SLIDE5]: Taiga's design principle titled "Global, inclusive and Accessible" highlighted over the rest.

And this is why making the next Taiga global, inclusive, and accessible is one of our design principles.
Why this goal? For starters, it is the right thing to do; making this a principle means it's not a way of achieving another goal. We want to make "the conversation" a central piece of our business model and design process. Everyone involved in a project should be able to participate on their own terms, and have space to share opinions and collaborate. And if we want this, we need Taiga to be global, inclusive and accessible.

[SLIDE6]: QR code to access the transcription of the talk, illustrated with an adorable polar bear sleeping over a log.

Before going ahead, this talk aims at the same thing, we'd like to make this presentation global, inclusive, and accessible. For those of you who are hearing impaired, or if my accent is difficult, you can find the transcription by using this QR code. You'll find a little description of the slides as well. A bit of accessibility that helps us all.

Now, you are wondering who ARE we and what IS Taiga? About time you asked! This is the conversation I was talking about, thank you folks.

Regarding the first question, I'm Miryam, one of the user experience designers at Taiga and also the product owner and I'm Yamila, chief operating officer at Kaleidos and backend developer at Taiga.

[SLIDE7]: Screen capture of the kanban of the new Taiga with the title "What is Taiga?"

To answer the second question, Taiga is an open source project management tool. You can try it, completely free, at taiga.io or install it on your own premises.

Back in 2013, when Kaleidos was a consulting company, we needed a tool where we could have relevant and fair conversations in the projects. I'm referring to everyone from customers expressing their needs to developers noting blocks (which happen) or sharing ideas (which also happen in an open environment). We wanted it to be open source, for sure. We wanted to work with agile methodologies. And we wanted it to be really beautiful, which was unexpected at that time. Yes, I'm looking at you, Jira. We compared different options, we didn't find what we were looking for, and so we built Taiga.

Currently we're working on the next generation of Taiga, where we bring those features and add innovation around lean methodologies and integration with Penpot. If you don't know what Penpot is, don't worry, we'll get into that later (grin).

Now, to sum up this introduction, in this talk we'll get into detail about how we are building a platform for multi-functional teams, where open conversations are encouraged as a means to create better products. Let me say this again, we want Taiga to be truly global, inclusive and accessible. All of this should ring a bell for those of you who appreciate how Penpot is bringing designers and developers into the same arena.

[SLIDE8]: A globe surrounded by the word "hi" in several languages with the title "Global" and the subtitle "Taiga is for everyone around the world".

So let's start with those principles. To make Taiga global, we have to think of different needs depending on the user's location.

First and foremost, it is crucial to have Taiga translated into different languages so the user can work in her own language or the language of her team. Typically, this would mean a bunch of Western languages, especially English, because everyone speaks English, right? But if you want to make your product really global, you have to open the catalog and include right-to-left languages as well. And you have to know which languages you want to include from the very beginning during the design process because it's not something that you can plug in at the last moment.

Besides internationalization, you have to think of different localizations, so the user may configure her date and timestamp formats, for instance.

Depending on the user's country or her company's security policies, she may be allowed to log in into a platform hosted in European data centers, and let it manage her project data; or she may be denied. So Taiga is offered as a cloud platform as well as an on-premise installation.

Kind of a side note (because that would require a whole new talk): it's not easy to make it global for everyone in every corner of the world. On one hand, we don't know everything and, on the other, we don't know what we don't know.

[SLIDE9]: A screen capture of the user's menu can choose the platform's language between several, including some Cyrillics, Arabics, Chinese...

So it's very important to have an open conversation with the community: they come from different parts of the globe, with requests and tips we couldn't have imagined. Now, in order to have relevant conversations with these motivated and also random people, we must share our product roadmap as well as the design and development process. And we have to provide some means for receiving requests. Luckily, these days, there are so many options to reach our communities.

One example of all these components working together is community driven translations. Taiga is ready to have as many languages as there are but we don't speak that many languages. We are not even native English speakers, although you barely noticed right? So, with the help of the community and thanks to being open source  (let's not forget that) we can have Taiga translated into any language so everyone will be able to work in the language of their choice.

[SLIDE10]: The title "Inclusive" and the subtitle "Taiga is for everyone in the project", illustrated by a penguin looking back at a glacier.

Up to this point we have a platform that can be potentially used everywhere. But we know that having a username and a password in a platform doesn't mean a user can speak up. Some people and some roles are more vocal and it gets difficult for others to participate in a project. Although Taiga cannot solve toxic relationships, it can offer a more inclusive scenario where all people have a voice which enables better collaboration.

To make Taiga inclusive, we try to use gender-neutral language. In English it's kind of easier, but in Spanish and other gender marked languages it's a challenge: we have to find new expressions that feel natural, but that are not too wordy to prevent our designers from wanting to retire because these sentences don't fit no matter what.

This gender-neutral decision has a welcome side effect: some... folks react poorly to this inclusion as it is "ideology" and they just want to work, as they always have. Well... (shrug).

In Taiga6 we use estimations to trigger a more inclusive decision-making mechanism: all roles are expected in an estimation, so not only developers set the deadlines. That way we can spotlight the work of designers, which is often ignored during plannings. We've all lived it and it's just bad for the project and the team morale.

Another scenario where we can facilitate the inclusion of different roles is regarding assignments. We see a lot of this old-fashioned style where there is a manager... managing, and other workers doing stuff. And there can sometimes be a huge chasm between these two groups in terms of transparency: a developer may only know her task and not know anything about the rest of the project. Instead, in Taiga Next a user cannot be "passively" assigned to a story unless she has access to all the stories of the project, and has the whole context.

That said, we want to take a step further in building relevant and fair conversations between designers, developers, and managers. Now, Miryam is going to tell us a little more about how we picture this collaboration.

[SLIDE11]: A mockup showing a kanban in Taiga and some boards in Penpot illustrates the link between both platforms.

Imagine that you are a designer on a project. For some of you, it won't be difficult at all. The product owner has created a series of stories on the Kanban, ready to start. You've completed your previous stories and now you are free to take a new one. You've read the requirements of this new story in Taiga, maybe you have questions and you use the comments to ask for clarification, improving the definition of the story. When everything is clear, wouldn't it be nice if you had access from Taiga to "design in Penpot" and it automatically creates a board in Penpot with the story id from Taiga and a label with the title? Both Penpot and Taiga pages would be linked making it easier to move between the definition and the design of the story. Nice, right?

Let's picture another situation: You put together some wireframes, on Penpot for example, and ask the development team to verify that the data treatment is consistent. The backend team checks the wireframes and puts some comments in Penpot, which triggers two things: a notification, but also a "needs info" tag that is added to the story in Taiga letting everyone involved know that there is an ongoing conversation. Maybe, it was a blocking issue and a manager jumps in to make a decision. So communication becomes more fluent.

As a result, a small but key change was needed and you can continue your work. You come back to Penpot, this time to do the final designs, enjoying the flex layout and the grid, knowing that pixel-perfect is just one svg away. When finished, in Penpot, you label those screens as "ready", so the story in Taiga changes to a status where a developer can pick it up and implement it.

In conclusion, all those small tweaks will improve your workflow. You will be able to get almost all of your work done within your main tool, Penpot. You won't need to switch contexts so often, and it will be natural and easy for other participants to access the artifacts you create and track the progress.

These are some examples of what it means for us, at Kaleidos, to focus on fair and relevant conversations for multidisciplinary teams.

At this point, the most important question to answer is: for the faucets, gold or bronze?

[SLIDE12]: Images of two faucets, one gold and one bronze
Yami: Are you for real?
Miryam: Ok, ok, Sorry.

[SLIDE13]: The title "Accessible" and the subtitle "Taiga is just for everyone" over some icons: an ear, an eye and a wheelchair.

The most important question is "What does it mean that Taiga is for all people?" It is not easy for us to answer this, although we have advanced a few steps in recent years, we still have a long way to go in terms of accessibility.

Our commitment to accessibility has not always been as strong as it is now. First, we weren't even totally aware of this need, since people with disabilities already have their own apps, right? We have not always taken into account the entire spectrum that our potential users represent, which is almost everyone! However, thanks to activists who explain why it is important, and a lot of continuous training, we continue incorporating accessibility needs into our mindset, both in design and development. The team takes ownership of this design principle.

We have learned how to face many technical aspects: colors and contrasts, of course, but also hierarchy, amount of data... And in the process, we have also unlearned some prejudices like the idea that an accessible design cannot be beautiful.

The cherry on top is that, by making an app more accessible, we make it better for all of our users, even those who didn't have accessibility needs, to begin with.

So, we are committed to creating a truly accessible product and that's why we have integrated accessibility as a base criteria to design each story. It is also in our definition of done. For us, a user story is not finished unless it, at minimum, can be handled without using the mouse, and the screen reader experience is satisfactory.

But I don't just mean doing the bare minimum for compliance, but also going the extra mile to make the experience enjoyable as well.

[ON SCREEN]: Taiga next

Let me show you an example. On screen, you can see the kanban of the new Taiga. This is how it goes. I'm moving cards around using the drag and drop and the mouse. Now, this is me doing the exact same thing but just with the keyboard. While doing this, if you were using a screen reader, you would hear all the necessary information when needed. That includes:

- Tips for discovering and remembering how to use the functionality
- Information on the state of the card at all times (is grabbed? has been dropped?)
- Key information about the story you took, such as the title and the id
- The position of the card, both the status and the priority, current and future.

As you have seen, I can use the functionality with some comfort, but I can also easily navigate through the kanban without having to go through each story. We are trying to offer an experience that is as enjoyable with the keyboard and the screen reader as it is with the drag and drop and the mouse. I hope this example illustrates what I mean by "going the extra mile and not just complying".

Now, take a good look at the design. Well, don't look TOO CLOSELY because it's still in alpha. When we look at this kanban, we don't see the sacrifices that accessible design is supposed to require. Instead, we see something intuitive, usable and beautiful that everyone can enjoy.

We also plan to add custom shortcuts, themes: high contrast for sure, and YES! A dark one; a skip-links system, ways to ensure enough contrast when the user sets colors for the rest of the team, for the statuses, for example... But what we think is really going to make a big difference is to offer alternative ways of doing everything whether you use a mouse, keyboard, voice, you name it.

All this being said, there is still a lot to do and tons of things to learn. This is just the beginning.

We are in the middle of an accessibility consultancy that is also a course. Remember that there are accessibility experts who can help you boost your knowledge and practice and you can hire them!

We also plan to start a series of tests, now that we have something more substantial.

But the tests won't just be about accessibility. We also have to check whether the colors, images, and illustrations are culturally appropriate and universal enough for everybody to understand, if we are using the correct date and hour formats and much much more.

Wish us luck!

[SLIDE14]: Taiga's design principle titled "Global, inclusive and Accessible" highlighted between some of the rest of the design principles.

Everything we have told you is only possible if the entire team is committed to this goal. That includes business, management, design and development. The efforts of any of these parties are of little use if they are not combined with the efforts of the entire team.

We are facing a big challenge; every time we dive deeper into the meaning of these words: global, inclusive, and accessible, it changes, it expands. The initial scope of this design principle a year ago was so much smaller than it is now, and that's overwhelming but beautiful at the same time.

It will require significant investment and hard work, we are already doing it, but we are so proud to pursue these goals! The task is huge, but we are learning, testing, and putting our hearts into it because we know it's worthwhile.

In Kaleidos we have lived through a "developer-centric" era when design was an otherness; however, right now we cannot imagine any project without a design team and one with a lot of decision-making power over the project. In the same way, we hope that qualities such as inclusivity or accessibility stop being otherness in software development and become the norm.

Well, that's all. Thank you for your time and attention and thank you, Penpot, again for giving us the opportunity to talk- about our stuff.

[SLIDE15]: Speakers' names and job titles: Yamila Moreno - COO at Kaleidos, Senior Backend at Taiga, and Miryam González Duque - Product Owner and UX Designer at Taiga. The word "Thanks!" Taiga's website: www.taiga.io The text: "Keep an eye out for the new Taiga at community.taiga.io"

If there are any questions about the presentation, we'll be more than happy to answer them. We and the rest of the team will be around if you want to come and share your experience with us.

If you have questions about the renovation, please, save them for later and proceed at your own risk. Thank you very much.
