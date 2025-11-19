[index.html](https://github.com/user-attachments/files/23613541/index.html)# index.html
directory
[Uploa<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>South Coast KZN Quick Reference Directory</title>
</head>
<body style="margin:30px; font-family:Arial, sans-serif; background:#f4f4f4;">

  <!-- HEADER -->
  <div style="background:#0066cc; color:white; padding:25px; text-align:center; border-radius:12px; margin-bottom:40px;">
    <h1 style="margin:0; font-size:30px;">South Coast KZN Quick Reference Directory</h1>
    <p style="margin:10px 0 0; font-size:18px;">Your free, fast-find local business guide</p>
  </div>

  <!-- LICENSEE FREE SPACE + BUTTON -->
  <div style="background:#f8f9fa; border:2px dashed #0066cc; padding:30px; text-align:center; border-radius:12px; margin-bottom:50px;">
    <h2 style="color:#0066cc; margin-top:0;">Licensee Free Space</h2>
    <p style="font-size:17px; margin-bottom:25px;">
      Claim your free listing below – every approved submission keeps this directory alive!<br>
      Watch ads to earn your own banner (or buy one instantly if you’re impatient 😉)
    </p>
    <button onclick="openForm()" style="background:#0066cc; color:white; padding:16px 36px; border:none; border-radius:8px; font-size:19px; cursor:pointer; box-shadow:0 5px 15px rgba(0,0,0,0.2);">
      Submit Your Free Listing
    </button>
  </div>

  <!-- POP-UP FORM -->
  <div id="listingForm" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.75); z-index:9999; overflow:auto;">
    <div style="background:white; width:90%; max-width:480px; margin:50px auto; padding:30px; border-radius:12px; position:relative; box-shadow:0 10px 40px rgba(0,0,0,0.3); max-height:90vh; overflow-y:auto;">
      <span onclick="document.getElementById('listingForm').style.display='none'" style="position:absolute; top:10px; right:20px; font-size:34px; cursor:pointer; color:#999;">×</span>
      <h2 style="text-align:center; color:#0066cc; margin-bottom:25px;">Submit Your Free Directory Listing</h2>

      <form action="https://formspree.io/f/xpzvlgkw" method="POST">
        <input type="hidden" name="_subject" value="New South Coast Directory Listing">
        <input type="hidden" name="_next" value="https://formspree.io/thank-you">

        <label>Main Category</label>
        <input type="text" name="Main Category" required style="width:100%; padding:10px; margin-bottom:12px;">

        <label>Sub-Category (internal)</label>
        <input type="text" name="Sub-Category" style="width:100%; padding:10px; margin-bottom:12px;">

        <label>Town / Area Line 1 (e.g. Hibberdene)</label>
        <input type="text" name="Town 1" required style="width:100%; padding:10px; margin-bottom:12px;">

        <label>Town / Area Line 2 (optional)</label>
        <input type="text" name="Town 2" style="width:100%; padding:10px; margin-bottom:12px;">

        <label>Company Name</label>
        <input type="text" name="Company Name" required style="width:100%; padding:10px; margin-bottom:12px;">

        <label>Slogan</label>
        <input type="text" name="Slogan" required style="width:100%; padding:10px; margin-bottom:20px;">

        <!-- Contact 1 – free choice -->
        <label>Contact 1 – Description (e.g. Reception / Emergency)</label>
        <input type="text" name="Label1" placeholder="e.g. Reception" required style="width:100%; padding:10px; margin-bottom:8px;">
        <select name="Colour1" style="width:100%; padding:10px; margin-bottom:8px;">
          <option value="#3498db" selected>Light Blue (usual)</option>
          <option value="#2ecc71">Green</option>
          <option value="#e74c3c">Red (Emergency)</option>
        </select>
        <input type="tel" name="Number1" required style="width:100%; padding:10px; margin-bottom:20px;">

        <!-- Contact 2 – WhatsApp locked green -->
        <label>Contact 2 – WhatsApp (always green)</label>
        <input type="text" name="Label2" value="WhatsApp" readonly style="width:100%; padding:10px; margin-bottom:8px; background:#f0f0f0;">
        <input type="hidden" name="Colour2" value="#2ecc71">
        <input type="tel" name="Number2" required style="width:100%; padding:10px; margin-bottom:30px;">

        <button type="submit" style="background:#0066cc; color:white; padding:16px; width:100%; border:none; border-radius:8px; font-size:19px;">Submit My Listing</button>
      </form>
    </div>
  </div>

  <script>
    function openForm() { document.getElementById('listingForm').style.display = 'block'; }
  </script>
  <!-- FIRST LIVE LISTING -->
<div style="margin-bottom:40px; font-family:Arial, sans-serif;">

  <div style="background:#f0f0f0; color:#555; padding:8px 12px; font-weight:bold; font-size:15px; border-radius:6px; text-align:center; margin-bottom:10px;">
    Animal Husbandry
  </div>

  <!-- grey category box -->

  <div style="background:#f9f9f9; border:1px solid #ddd; padding:8px 12px; border-radius:5px; font-size:14px; line-height:1.5; text-align:center; margin-bottom:10px;">
    min-height:50px;">
    Hibberdene<br>Port Shepstone area
  </div>

  <div style="background:#ffffff; border:1px solid #ddd; padding:10px 14px; border-radius:5px; font-size:20px; font-weight:bold; color:#1a1a1a; text-align:right; margin-bottom:8px;">
    Hibberdene Kennels & Cattery
  </div>

  <div style="font-size:14px; color:#555; font-style:italic; text-align:right; margin-bottom:12px; margin-right:14px;">
    Loving care for your fur babies
  </div>

  <div style="background:#ffffff; border:1px solid #ddd; padding:10px 14px; border-radius:5px; font-size:15px;">
    <span style="color:#e74c3c;">Emergency:</span> 039 699 8040 &nbsp;&nbsp;|&nbsp;&nbsp; 
    <span style="color:#2ecc71;">WhatsApp:</span> 078 624 2964
  </div>
  
  <div style="text-align:center; margin-top:60px; padding:20px; background:#f8f9fa; border-top:3px solid #0066cc; font-size:14px; color:#555;">
  © 2025 Ruth Temple-Murray · South Coast KZN Quick Reference Directory™<br>
  All content, design, format and concept are the exclusive intellectual property of the author.<br>
  Unauthorised reproduction, distribution or commercial use strictly prohibited.
</div>

</div>
<br><br>

</body>
</html>

ding index.html…]()
