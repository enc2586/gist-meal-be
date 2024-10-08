# gist-meal-be

**GIST Meal Backend**

This project, `gist-meal-be`, is the backend of the `gist-meal` website. It provides the API endpoints for managing and serving the daily meal menus for GIST college cafeterias. The backend is built to support both Korean and English users, allowing easy data management and access.

## Features

- RESTful API for daily meal menus.
- Supports multiple cafeterias and meal periods.
- Bilingual support for Korean and English.

## Installation and Running Locally

To run this project locally, you will need `Node.js` and `npm` (or `yarn`) installed.

### Step 1: Clone the Repository

```bash
$ git clone https://github.com/your-username/gist-meal-be.git
$ cd gist-meal-be
```

### Step 2: Install Dependencies

```bash
$ npm install
```

### Step 3: Set Up Environment Variables

Create a `.env` file at the root of your project with the following contents:

```
PORT=5000
DATABASE_URL=<YOUR_DATABASE_URL>
```

Replace `<YOUR_DATABASE_URL>` and `<YOUR_JWT_SECRET>` with your actual database connection URL and secret key for JWT.

### Step 4: Run the Development Server

```bash
$ npm start:dev
```

After running the above command, the API will be available at `http://localhost:5000`.

## Available Scripts

- `npm start:dev`: Runs the server in development mode.
- `npm run build`: Prepares the server for production.

## Contributing

Contributions are welcome! Please feel free to open issues or pull requests.

## License

This project is licensed under the GNU General Public License v3.0. See the LICENSE file for details.

## Contact

For any questions or suggestions, please contact [enc2586@gmail.com].

---

# gist-meal-be

**GIST 식단 백엔드**

`gist-meal-be`는 GIST 대학 식당의 일일 식단을 관리하고 제공하는 `gist-meal` 웹사이트의 백엔드입니다. API 엔드포인트를 통해 데이터를 관리하며, 한국어와 영어를 지원합니다.

## 주요 기능

- 일일 식단을 위한 RESTful API.
- 여러 식당 및 식사 시간대 지원.
- 한국어와 영어를 지원하는 이중 언어 기능.

## 설치 및 로컬 실행 방법

이 프로젝트를 로컬에서 실행하려면, `Node.js`와 `npm` (또는 `yarn`)이 필요합니다.

### 1단계: 리포지토리 클론하기

```bash
$ git clone https://github.com/your-username/gist-meal-be.git
$ cd gist-meal-be
```

### 2단계: 의존성 설치

```bash
$ npm install
```

### 3단계: 환경 변수 설정

프로젝트 루트에 `.env` 파일을 생성하고 다음 내용을 추가하세요:

```
PORT=5000
DATABASE_URL=<YOUR_DATABASE_URL>
```

`<YOUR_DATABASE_URL>` 및 `<YOUR_JWT_SECRET>`을 실제 데이터베이스 연결 URL과 JWT 비밀 키로 변경하세요.

### 4단계: 개발 서버 실행

```bash
$ npm start:dev
```

위 명령을 실행한 후, `http://localhost:5000`에서 API를 사용할 수 있습니다.

## 사용 가능한 스크립트

- `npm start:dev`: 개발 모드에서 서버를 실행합니다.
- `npm run build`: 프로덕션용 서버를 준비합니다.

## 기여하기

기여는 언제나 환영합니다! 이슈나 풀 리퀘스트를 자유롭게 열어 주세요.

## 라이선스

이 프로젝트는 GNU 일반 공중 사용 허가서 v3.0에 따라 라이선스가 부여되어 있습니다. 자세한 내용은 LICENSE 파일을 참조하세요.

## 문의

질문이나 제안 사항이 있다면 [enc2586@gmail.com]으로 연락해 주세요.
