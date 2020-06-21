---
layout: page
title: Contact
permalink: /contact/
nav_order: 99
---

# Contact

<form accept-charset="UTF-8" action="https://getform.io/{YOUR_UNIQUE_FORM_ENDPOINT}" method="POST" target="_blank">
      <div class="table-wrapper">
            <table>
                <tbody>
                    <tr>
                        <td><label for="inputName">Name</label></td>
                        <td><input type="text" name="name" class="form-control" id="inputName" placeholder="Your name" required="required"></td>
                    </tr>
                    <tr>
                        <td><label for="inputEmail">Email address</label></td>
                        <td><input type="email" name="email" class="form-control" id="inputEmail" aria-describedby="emailHelp" placeholder="Your email" required="required"></td>
                    </tr>
                    <tr>
                        <td><label for="feedbackType">Feedback subject</label></td>
                        <td>
                            <select class="form-control" id="feedbackType" name="feedbacktype">
                              <option>General</option>
                              <option>Cloudtrail Viewer</option>
                              <option>Ends</option>
                            </select>
                        </td>
                    </tr>
                    <tr>
                        <td><label for="feedback">Feedback</label></td>
                        <td><textarea name="feedback" class="form-control" id="feedback" placeholder="Your feedback" required="required"></textarea></td>
                    </tr>
                    <tr>
                        <td colspan="2"><button type="submit" class="btn btn-primary">Submit</button></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </form>