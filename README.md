# Railsgram

## Getting Started

Follow these steps to set up and run the Railsgram app on a Unix-based system.

### Prerequisites

Ensure you have the following installed on your system:
- **Ruby** (Recommended: Latest stable version)
- **Bundler** (`gem install bundler` if not installed)
- **Node.js & Yarn** (for JavaScript dependencies)
- **PostgreSQL** (if your app uses it)

### Installation

1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/railsgram.git
   cd railsgram
   ```

2. **Install Dependencies**
   ```sh
   bundle install
   yarn install
   ```

3. **Setup the Database** (if applicable)
   ```sh
   rails db:migrate
   ```

4. **Start the Development Server**
   ```sh
   bin/dev
   ```
