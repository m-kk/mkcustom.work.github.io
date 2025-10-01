---
layout: page
icon: fas fa-envelope
order: 5
title: Contact & Custom Orders
---

## Request a Custom Design

Need a 3D printed solution? Fill out the form below or email directly with your project details.

<div class="page-contact">
  <form action="https://formspree.io/f/mgvnkjer" method="POST" class="contact-form">
    <div class="form-group">
      <label for="name">Name <span class="required">*</span></label>
      <input 
        type="text" 
        name="name" 
        id="name" 
        required 
        placeholder="John Doe"
        autocomplete="name"
      >
    </div>

    <div class="form-group">
      <label for="email">Email <span class="required">*</span></label>
      <input 
        type="email" 
        name="email" 
        id="email" 
        required 
        placeholder="john@example.com"
        autocomplete="email"
      >
    </div>

    <div class="form-group">
      <label for="order-type">Order Type <span class="required">*</span></label>
      <select name="order-type" id="order-type" required>
        <option value="">Select one...</option>
        <option value="Stock Design">Stock design from catalog</option>
        <option value="Custom Design">Custom design needed</option>
        <option value="Modification">Modify existing design</option>
        <option value="Bulk Order">Bulk/multiple units</option>
        <option value="Question">General question</option>
      </select>
    </div>

    <div class="form-group">
      <label for="material">Preferred Material</label>
      <select name="material" id="material">
        <option value="">Not sure / recommend for me</option>
        <option value="PETG">PETG (functional, durable)</option>
        <option value="PLA">PLA (aesthetic, eco-friendly)</option>
        <option value="ABSASA">ABS/ASA (outdoor, heat-resistant)</option>
      </select>
    </div>

    <div class="form-group">
      <label for="message">Project Details <span class="required">*</span></label>
      <textarea 
        name="message" 
        id="message" 
        rows="8" 
        required 
        placeholder="Tell me about your project..."
      ></textarea>
      <small style="display: block; margin-top: 0.5rem; color: var(--text-muted); font-size: 0.875rem;">
        Include: What you need, dimensions (if known), quantity, and timeline
      </small>
    </div>

    <!-- Honeypot for spam protection -->
    <input type="text" name="_gotcha" style="display:none" tabindex="-1" autocomplete="off">
    
    <!-- Hidden subject line -->
    <input type="hidden" name="_subject" value="New mkcustom.work order inquiry">

    <input type="hidden" name="_next" value="https://mkcustom.work/thanks">

    <button type="submit" class="btn">Submit Request</button>
  </form>
</div>
---

### Direct Email

**[matt@mkcustom.work](mailto:matt@mkcustom.work)**

**Response time:** Usually within 24 hours

---

### What Happens Next?

1. **I'll review your request** and may ask clarifying questions
2. **Design & quote** - You'll receive a 3D model preview and price quote
3. **Approval** - Once approved, I'll print and ship within 3-5 business days

### Helpful to Include

- **Photos** of the space or item (helps with sizing)
- **Measurements** if you have them
- **Color preference** (I stock common colors)
- **Timeline** if you need it by a specific date

### Local Pickup

In the Chicago area? Local pickup available to save on shipping!
