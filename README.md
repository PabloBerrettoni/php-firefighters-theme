> Wordpress Pukara starter theme

## Usage

#### 1. Clone the repository

```bash
git clone https://github.com/PukaraES/wordpress-boilerplate.git
```

#### 2. Remove the .git folder

```bash
cd wordpress-boilerplate && rm -rf .git/
```

#### 3. Configure your envs and start the local dev environment with docker-compose

```bash
docker-compose up -d
```

#### 4. Install theme dependencies

```bash
cd themes/pukara-theme && yarn
```

#### 5. Run gulp script to compile assets inside the theme folder

```bash
npx gulp
```

#### 6. Compress the files inside the firefightersTheme

- Whe compressing the files you need to ensure that the .zip is named "firefightersTheme.zip"

### 7. Upload the theme to your wordpress

### 8. Complete the information required in theme customization

- You will need to fill all the fields with the respective information from onesignal and pusher

### 9. Start using your new wordpress theme

