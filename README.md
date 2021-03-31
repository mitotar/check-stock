# check-stock

<img src="sample.gif" style="width:80%"/>

## Automatically check the stock status of products

### Supported websites:

-   <a href="https://www.chapters.indigo.ca/en-ca/">chapters.indigo.ca</a>
-   <a href="https://www.lego.com/en-ca/">lego.com</a>

NOTE: You need python3 and all modules used in `app.py` and `check_stock.py` installed on your machine to be able to run this program.

### To run:

1. Open the terminal and navigate to the `check-stock` folder.
2. Run the following line:
    ```shell
    python3 app.py
    ```

### To run on Mac, without terminal (mostly):

1. Open Finder and navigate to the location of this folder (`check-stock`).
2. Double-click the file `app.command`. This will launch your terminal.<br>
    - If this gives you an "unidentified developer" error, right-click the file, choose Open > Open.
3. Displayed in your terminal will be a line similar to the following:
    ```shell
    * Running on http://111.0.0.1:1000/ (Press CTRL+C to quit)
    ```
    Copy this http link into your browser of choice.
4. To quit the program, press <kbd>⌃ control</kbd> + <kbd>C</kbd> in your terminal, and close the browser window.

If you get a permission error at step 2, do the following then continue above with step 3:

1. Open Terminal (<kbd>⌘ command</kbd> + <kbd>space</kbd>, type in 'Terminal', press <kbd>enter</kbd>).
2. Navigate to the `check_stock` folder.
3. Run the following command:
    ```shell
    chmod 111 app.command
    ```

### Statuses

Available for shipping:

-   Free shipping on orders over $35

Not available for shipping:

-   On re-order online
-   Out of stock online

<br><br>

## To-do

1. Find out what's happening with Lego set 21318 stock status discrepancy between app and website
2. `check_stock.command` file opens two application tabs. Not sure why.
3. Add option to change "nickname" of product
4. Make compatible with other online stores
5. Automatically run this program every set amount of time and send notification
