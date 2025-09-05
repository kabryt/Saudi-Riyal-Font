# Saudi-Riyal-Font
Saudi Riyal Font AbuZiad - Used under SIL Open Font License 1.1

This font allows you to use the Saudi Riyal currency symbol in websites, applications, and documents, ensuring compatibility in cases where the underlying system does not support this currency symbol.  Its use is very simple; simply use the code e900.

Example:


    <style>
        @font-face {
            font-family: 'Kabryt';
            src: url('Kabryt-bold.ttf') format('truetype');
            font-weight: normal;
            font-style: normal;
        }

        .icon {
            font-family: 'Kabryt', sans-serif;
            font-size: 20px;
        }

        .icon::before {
            content: "\e900";
        }
    </style>

    <h1>Custom Font Symbol Example</h1>

    <p>This is the symbol from the Kabryt font for use new Saudi Riyal symbol code e900:</p>
    <span class="icon"></span>
```
