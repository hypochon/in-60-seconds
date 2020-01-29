# Let's Get **Started**

---

### Add Some Slide Candy

![IMAGE](assets/img/presentation.png)

---?color=linear-gradient(180deg, white 75%, black 25%)
@title[Customize Slide Layout]

@snap[west span-55]
## Customize the Layout
@snapend

@snap[north-east span-45]
![IMAGE](assets/img/presentation.png)
@snapend

@snap[south span-100]
Snap Layouts let you create custom slide designs directly within your markdown.
@snapend

---
@title[Add A Little Imagination]

@snap[north-west span-50 text-center]
#### Engage your Audience
@snapend

@snap[west span-55]
@ul[list-spaced-bullets text-09]
- You will be amazed
- What you can achieve
- With a **little imagination**
- And GitPitch Markdown
@ulend
@snapend

@snap[east span-45]
![IMAGE](assets/img/conference.png)
@snapend

@snap[south span-100 bg-black fragment]
@img[shadow](assets/img/conference.png)
@snapend

---

@snap[north-east span-100 text-pink text-06]
Let your code do the talking!
@snapend

```sql zoom-18
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id
FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");
```

@snap[south span-100 text-gray text-08]
@[1-5](You can step-and-ZOOM into fenced-code blocks, source files, and Github GIST.)
@[6,7, zoom-13](Using GitPitch live code presenting with optional annotations.)
@[8-9, zoom-12](This means no more switching between your slide deck and IDE on stage.)
@snapend


---?image=assets/img/code.jpg&opacity=60&position=left&size=45% 100%

@snap[east span-50 text-center]
## Now It's **Your** Turn
@snapend

@snap[south-east span-50 text-center text-06]
[Download GitPitch Desktop @fa[external-link]](https://gitpitch.com/docs/getting-started/tutorial/)
@snapend

---

# Test 

---

## hui 

<iframe width="560" height="315" src="https://www.neuhland.net" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

# Was **los?**

+++ 

# Nichts
## Oder? 

+++ 

maybe
# Alter

--- 

# Ab*so*lut

---

@snap[north-west span-35]
@box[bg-green text-white box-padding fragment](1. Plan#Lorem ipsum dolor sit amet eiusmod)
@snapend

@snap[north-east span-35]
@box[bg-orange text-white rounded box-padding fragment](2. Build#Sed do eiusmod tempor labore)
@snapend

@snap[south-east span-35]
@box[bg-pink text-white box-padding](3. Measure#Cupidatat non proident sunt in)
@snapend

@snap[south-west span-35]
@box[bg-blue text-white waved box-padding](4. Repeat#Ut enim ad minim veniam prodient)
@snapend

@snap[midpoint]
@box[bg-blue text-white waved box-padding](5. Repeat#Ut enim ad minim veniam prodient)
@snapend

---

---

<canvas data-chart="pie">
<!--
{
 "data": {
  "labels": ["January"," February"," March"," April"," May"," June"," July"],
  "datasets": [
   {
    "data":[65,59,80,81,56,55,40],
    "label":"Sample Data X",
    "backgroundColor":"rgba(20,220,220,.8)"
   },
   {
    "data":[28,48,40,19,86,27,90],
    "label":"Sample Data Y",
    "backgroundColor":"rgba(120,220,0,.8)"
   }
  ]
 },
 "options": { "responsive": "true" }
}
-->
</canvas>

---?color=linear-gradient(65deg, red 35%, black 65%)

@snap[west span-40 text-center]

### GraphQL
@fa[quote-left quote-graphql](A query language for your API)
![GRAPHQL](assets/img/graphql.png)

@snapend

@snap[north-east span-40 text-08]
@box[bg-green](Step 1. Schema # Define types using SDL)
@snapend

@snap[east span-40 text-08]
@box[bg-blue](Step 2. Query # Fetch data with Queries)
@snapend

@snap[south-east span-40 text-08]
@box[bg-gold](Step 3. Mutate # Modify data with Mutations)
@snapend
