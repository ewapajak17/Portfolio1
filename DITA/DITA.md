# Write in DITA <!--omit in toc-->

## Install Oxygen XML Author

- [Write in DITA ](#write-in-dita-)
  - [Install Oxygen XML Author](#install-oxygen-xml-author)
  - [Create a Project](#create-a-project)
  - [Create a DITA Map](#create-a-dita-map)
  - [Create a Topic](#create-a-topic)
  - [Reference the Topic from the Map](#reference-the-topic-from-the-map)
  - [Transform the DITA XML into Deliverable Input Format](#transform-the-dita-xml-into-deliverable-input-format)
  - [Reference a Map](#reference-a-map)
  - [Configure Oxygen XML Author to Use Profiling](#configure-oxygen-xml-author-to-use-profiling)
    - [Adjust Settings](#adjust-settings)
    - [Profile a DITA Map](#profile-a-dita-map)
    - [Profile a Topic](#profile-a-topic)
    - [Profile a Topic Item](#profile-a-topic-item)
    - [Profile a Table Row](#profile-a-table-row)


1. Go to https://www.oxygenxml.com/.
2. From the **Products** drop-down, select **XML Oxygen Author**.
3. Click **Download**.
4. Complete the text boxes: Email and Country.
5. Click **Get Trial License** to get the 30-day trial license.

## Create a Project

1. Open XML Oxygen Author on your computer.
2. In the top navigation bar, click **Project** > **New project**.

   √ A **New project** window opens.
3. Click **Default project**.
4. In the **Project file name**, type _Training project_.
5. In the **Project directory**, click the **Browse** icon and choose the location.
6. Click **Choose**.
7. Click **Create**.

## Create a DITA Map

1. In the top navigation bar, click **File** > **New** (or press Ctrl+N).

   √ A **New** window opens.
2. In the search text box, type _map_.
3. Scrol down the list and choose **Map**.

![image](https://github.com/ewapajak17/Portfolio/assets/144762179/0d00277b-5db4-484b-a7e9-b43631cdfd61)

4. In the **Title**, type _Training-map-1_.
5. Click **Create**.

   √ A **Select editor** window opens.
6. Click **DITA Maps Manager**.

## Create a Topic

1. In the top navigation bar, click **File** > **New** (or press Ctrl+N).

   √ A **New** window opens.
2. Double click **Topics**.
3. Click **Task**.
4. In the **Title**, type _the title_.
5. Click **Create**.

## Reference the Topic from the Map

1. In the bottom navigation bar, click **DITA Maps Manager**.
2. Right-click **Training-Map-1** on the left-side menu.
3. In the drop-down, hover over **Apend child**.
4. Click **Reference**.
5. In the **Reference Type** drop-down, select **Topic Reference**.
6. In **Target**, select the name of your topic from the list.
7. Click **Insert and close**.
8. Click the **Save** icon (or press Ctrl+S).

## Transform the DITA XML into Deliverable Input Format

1. In the bottom navigation bar, click **DITA Maps Manager**.
2. In the left-side navigation bar, click the **Configure Transformation Scenario** icon.

   √ A **Configure Transformation Scenario** window opens.
3. Select the **DITA Map PDF - based on HTML5 & CSS** check box.
4. Click **Apply Associated (1)**.

    √ A PDF version opens in a separate window.

    Note: Click the **Apply Transformation Scenario** icon to get the PDF version.

## Reference a Map

1. Go to [Create a DITA Map](#Create-a-DITA-Map), follow the steps and name the map as _Reusable Map_.
2. Go to [Create a Topic](#Create-a-Topic), follow the steps and name the topic as _Reusable Topic.
3. Go to [Reference the Topic from the Map](#Reference-the-Topic-from-the-Map).
4. Right-click **Training-Map-1** on the left-side menu.
5. In the drop-down, hover over **Append child**.
6. Click **Map Reference**.

   √ An **Insert Map Reference** window opens.
7. Select **Reusable Topic**.
8. Click **Insert and close**.

   √ You will see the structure of your map in DITA Maps Manager. Drag and drop to change the order.

## Configure Oxygen XML Author to Use Profiling

### Adjust Settings

1. Click the topic you want to edit in the top list.
2. Click the **Profiling/Conditional Text** icon.
3. From the drop-down, click **Show Profiling Colors and Styles**.

   √ A **Show Profiling Colors and Styles** window opens.
4. Click **Close**.
5. Click the **Profiling/Conditional Text** icon.
6. From the drop-down, click **Show Profiling Attributes**.
7. From the drop-down, click **Show excluded content**.
8. From the drop-down, click **Profile Settings**.

   √ A **Preferences** window opens.
9. Click **Colors and Styles**.
10. In **Defined Attributes Value**, click and mark 10 lines on the list.
11. Click **Automatic Styling**.
12. Click **OK**.

### Profile a DITA Map

**Note**: Make sure you have adjusted the settings first. Go to [Adjust Settings](#Adjust-Settings)

1. In DITA Maps Manager, right-click the map you want to profile.
2. Click **Edit Properties**.
3. Click **Profiling**.
4. In **Audience**, check **expert**.

   √ The map will be relevant for expert users.
5. Click **OK**.

### Profile a Topic

**Note**: Make sure you have adjusted the settings first. Go to [Adjust Settings](#Adjust-Settings)

1. In DITA Maps Manager, right-click the topic you want to profile.
2. Click **Edit Properties**.
3. Click **Profiling**.
4. In **Audience**, check **novice**.

   √ The topic will be relevant for novice users.

### Profile a Topic Item

**Note**: Make sure you have adjusted the settings first. Go to [Adjust Settings](#Adjust-Settings)

1. Triple-click the selected element of the topic.
2. Right-click the marked element.
3. Click **Edit Profiling Attributes**.

   √ An **Edit Profiling Attributes** window opens.
4. In **Audience**, check **expert**.
5. Click **OK**.

### Profile a Table Row

1. Click the selected table row on the left.
2. Right-click the marked row.
3. Click **Edit Profiling Attributes**.

   √ An **Edit Profiling Attributes** window opens.
4. In **Audience**, check **expert** or **novice**.

   **Note**: Click the **Text** view on the bottom to check whether the row is assigned a novice or expert audience. Do not profile a single cell but you may profile the content of the cell, eg. the paragraph inside a cell.