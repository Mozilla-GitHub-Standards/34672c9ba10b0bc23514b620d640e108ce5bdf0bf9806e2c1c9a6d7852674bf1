<!-- <short-description> -->
The **HTML `<dialog>` element** represents a dialog box or other
interactive component, such as an inspector or window.
<!-- </short-description> -->

<!-- <overview> -->
<!-- </overview> -->

<!-- <usage-notes> -->
Usage notes
-----------

-   `<form>` elements can be integrated within a dialog by specifying
    them with the attribute `method="dialog"`. When such a form is
    submitted, the dialog is closed with its
    [`returnValue`](/en-US/docs/Web/API/HTMLDialogElement/returnValue)
    attribute set to the `value` of the form\'s submit button that was
    used.
-   The
    [`::backdrop`](/en-US/docs/Web/CSS/::backdrop)
    CSS pseudo-element can be used to style behind a `<dialog>` element,
    for example to dim inaccessible content whilst a modal dialog is
    active. The backdrop is only drawn when the dialog element is
    displayed with
    [`HTMLDialogElement.showModal()`](/en-US/docs/Web/API/HTMLDialogElement/showModal).
<!-- </usage-notes> -->

<!-- <see-also> -->
See also
--------

-   The `close` event
-   The `cancel` event
-   [HTML forms guide](/en-US/docs/Web/Guide/HTML/Forms).
-   The [`::backdrop`](/en-US/docs/Web/CSS/::backdrop) pseudo-element
<!-- </see-also> -->
