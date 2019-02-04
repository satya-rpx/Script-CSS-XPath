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

    ![](https://www.w3.org/TR/CSS21/images/doctree.png)

* ###  **Child**

  ![](https://sebastian.expert/wp-content/uploads/2015/01/hierarchy_tags_parent.png)

  * **ul** *is a child for* **div**
    **div** *is a child for* **body**.

* ### **Descendant**

  ![](https://sebastian.expert/wp-content/uploads/2015/01/hierarchy_tags_Descendant.png)

  * **p** has *one descendant* – **strong**
    **div** has *4 descendants* – **ul, li, li, li**
    **h2** has no descendants.

* ### **Ancestor**

  ![](https://sebastian.expert/wp-content/uploads/2015/01/hierarchy_tags_Ancestor.png)

  * **p, div and body** *are ancestors of* **strong**
    **div and body** *are ancestors of* **ul**
    **body** is an ancestor for both **strong** and **ul**
    **body** is the ancestor of all other elements in the tree.

* ### **Sibling**

  ![](https://sebastian.expert/wp-content/uploads/2015/01/hierarchy_tags_Siblings.png)

  * **h1, p, img and h2** *are siblings* as they share the same parent **div**
    **ul** *has no sibling* as its parent **div** does not have any other child element.