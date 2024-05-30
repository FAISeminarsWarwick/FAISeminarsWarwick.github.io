# How to Work with `FAISeminarsWarwick.github.io` on Your Localhost

## Prerequisites

Before you begin, ensure you have the following software installed on your machine:

1. **Git**: For cloning the repository.
2. **Node.js and npm**: For managing packages and dependencies.
3. **Jekyll**: A static site generator (optional, based on the project's setup).
4. **Conda**: For managing the environment.

## Steps to Set Up and Run the Repository Locally

### 1. Create a Conda Environment

Open your terminal and run the following commands to create and activate a Conda environment:

```bash
conda create --name faiseminarsenv python=3.11
conda activate faiseminarsenv
```

### 2. Clone the Repository

Clone the repository from GitHub:

```bash
git clone https://github.com/FAISeminarsWarwick/FAISeminarsWarwick.github.io.git
```

### 3. Navigate to the Project Directory

Change your current directory to the project directory:

```bash
cd FAISeminarsWarwick.github.io
```

### 4. Install Dependencies

If the Project Uses Node.js (Check for a package.json file)

Install the necessary npm packages:

```bash
npm install
```

If the Project Uses Jekyll (Check for Jekyll Configuration Files)

Install Jekyll and bundler gems:

```bash
gem install bundler jekyll
```

Then, install the dependencies listed in the Gemfile:

```bash
bundle install
```

### 5. Run the Project Locally

If Using Node.js (Check for npm Scripts in package.json)

Start the local server using npm:

```bash
npm start
```

If Using Jekyll

Serve the website locally:

```bash
bundle exec jekyll serve
```

### 6. Access the Local Server

Open your web browser and navigate to "localhost:4000" (the port number may vary based on the setup). You should see the website running locally.

**PS:** If this does not work, please set up [Jekyll Server.](install_server.md)

## Making Changes and Pushing to GitHub

### 1. Make Your Changes

Edit the files as needed using your preferred code editor.

### 2. Stage and Commit Your Changes

Once you've made your changes, stage them for commit:

```bash
git add .
```

Commit your changes with a descriptive message:

```bash
git commit -m "Description of the changes made"
```

### 3. Push Changes to GitHub

Push your changes to the repository:

```bash
git push origin main
```

Note: Replace main with the appropriate branch name if you're working on a different branch.
