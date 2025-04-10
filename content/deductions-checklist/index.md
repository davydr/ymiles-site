---
title: "Uber Driver Tax Deductions"
---

## Uber Driver Deductions Checklist

As a part-time Uber driver, one of the easiest ways to reduce your tax bill is by claiming the right deductions. This checklist breaks them into three categories to make filing simple.


### 1. **Mileage Log Book (Built with My Tool)**

The IRS requires a **log book** to claim mileage deductions. If you're ever audited, a general summary from Uber is **not enough** — it must show dates, miles, and purpose of each trip. That's where my tool comes in.

It doesn't just build your **IRS-compliant log book** — it also helps uncover **hidden miles** Uber doesn’t track, like:
- **Deadhead miles** for certain longer trips  (Hidden miles not covered under Uber online miles)
- Mileage of each trip with pickup and dropoff (Miles covered under uber online miles)
- Miles driving to and from passenger pickups/dropoffs (Miles covered under Uber online miles)
- Miles spent repositioning between cities or hotspots (Hidden miles not covered under Uber online miles)

These “hidden miles” can add hundreds of deductible dollars.
If you are using a mileage app you are creating a log book and you should be covered under an audit. The biggest difference is the tool will gather all of the data for hthe year then look through the data andask if certain trips shuld be converted to dead head miles versus you have to keep track of every ride in the app and tag it as an Uber ride before you wait a week and forget if the trip was for a passenger or yourself or somethign else.

In 2024, the IRS allows **67 cents per mile** — so every extra mile counts. With my tool, you don’t just track what Uber gives you; you build a full, defensible record and maximize your deduction. That’s why this log book is first on the checklist: it’s the biggest and easiest way to reduce your tax bill — and stay compliant if the IRS ever asks questions.

---

Let me know if you'd like to refresh the rest of the checklist to match this tone, or if you want a version that ends with a link to download the tool or checklist.

### 2. **Deductions You’re Probably Already Tracking**  
Some expenses are regular bills you’re likely already paying and recording:
- A portion of your **cell phone plan**
- **Data or hotspot usage** while driving
- **Spotify or music subscriptions** used during rides

You’ll deduct the business-use portion of these.

### 3. **Receipts-Required Deductions**  
Other items require more effort — you need a receipt to claim them:
- **Phone cables, chargers, and mounts**
- **Car cleaning or detailing**
- **Snacks and water** provided for riders
- **First aid kits, tissues, or floor mats**

These are small but add up over time. Keep those receipts or use an app to scan them as you go.


<form id="ymiles-form">
  <label for="email">Enter your email to get the checklist:</label><br>
  <input type="email" name="email" id="email" required>
  <button type="submit">Get Checklist</button>
</form>

<script>
  const scriptURL = "https://script.google.com/macros/s/AKfycbxSj3bQyEzqkYWQ-bSMcB64TD5qIPCQn06k8jkPHxsMb6TOLRnth8E-bc4bTxCVl7qrsg/exec"; // Replace with your web app URL
  const redirectURL = "/checklist-thankyou"; // Replace with your actual page

  document.getElementById("ymiles-form").addEventListener("submit", function(e) {
    e.preventDefault();
    const formData = new FormData();
    formData.append("email", document.getElementById("email").value);

    fetch(scriptURL, {
      method: "POST",
      body: formData
    })
    .then(response => response.text())
    .then(result => {
      if (result.trim() === "success") {
        window.location.href = redirectURL;
      } else {
        alert("Something went wrong. Please try again.");
      }
    })
    .catch(error => {
      alert("Error submitting form.");
      console.error("Error!", error.message);
    });
  });
</script>


