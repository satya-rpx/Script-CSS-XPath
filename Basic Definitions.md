# Basic Definitions

* **Document tree**

  * ```HTML
    <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN">
    <HTML>   
      <TITLE>My home page</TITLE>
      <BODY>
        <H1>My home page</H1>
        <P>Welcome to my home page! Let me tell you about my favorite
    		composers:
        <UL>
          <LI> Elvis Costello
          <LI> Johannes Brahms
          <LI> Georges Brassens
        </UL>
      </BODY>
    </HTML>
    ```

  * ![](C:\Users\satyakrishnak\Downloads\doctree.png)

* ###  **Child**

  * ![](C:\Users\satyakrishnak\Downloads\hierarchy_tags_parent (1).png)
  * **ul** *is a child for* **div**
    **div** *is a child for* **body**.

* ### **Descendant**

  * ![](C:\Users\satyakrishnak\Downloads\hierarchy_tags_Descendant.png)
  * **p** has *one descendant* – **strong**
    **div** has *4 descendants* – **ul, li, li, li**
    **h2** has no descendants.

* ### **Ancestor**

  * ![](C:\Users\satyakrishnak\Downloads\hierarchy_tags_Ancestor.png)
  * **p, div and body** *are ancestors of* **strong**
    **div and body** *are ancestors of* **ul**
    **body** is an ancestor for both **strong** and **ul**
    **body** is the ancestor of all other elements in the tree.

* ### **Sibling**

  * ![](C:\Users\satyakrishnak\Downloads\hierarchy_tags_Siblings.png)
  * **h1, p, img and h2** *are siblings* as they share the same parent **div**
    **ul** *has no sibling* as its parent **div** does not have any other child element.