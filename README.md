# Capital City Quiz

A web-based quiz game that tests your knowledge of world capitals. Built with Node.js, Express, EJS, and PostgreSQL.

## Features

- Randomly selects a country and asks for its capital.
- Tracks your score for correct answers.
- Game ends on a wrong answer, displaying your final score.
- Responsive and visually appealing UI.

## Setup

1. **Clone the repository**  

   ```sh
   git clone <repo-url>
   cd World+Capital+Quiz
   ```

2. **Install dependencies**

    ```sh
    npm install
    ```

3. **Set up PostgreSQL database**

- Create a database named `world`.
- Import `capitals.csv` into a table named `capitals` with columns: `id`, `country`, `capital`.

4. **Configure database credentials**

- Update the credentials in `index.js` if needed.

5. **Run the app**

    ```
    node index.js
    ```

- The server will run at `http://localhost:3000`.

## Usage

- Open the app in your browser.
- Enter the capital city for the displayed country.
- Your score increases for each correct answer.
- The game ends when you submit a wrong answer.

## Dependencies

- express
- ejs
- body-parser
- pg
- axios

## License

- This project is created for educational purpose.
