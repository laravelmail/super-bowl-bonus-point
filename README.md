# Super Bowl Bonus Point

Professional email template for announcing a Super Bowl Bonus Points event in the Technology or Entertainment industry.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Technology, Entertainment
- **Message Type:** Events
- **Tags:** superbowl, bonuspoints

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/super-bowl-bonus-point.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/super-bowl-bonus-point/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.super-bowl-bonus-point',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
