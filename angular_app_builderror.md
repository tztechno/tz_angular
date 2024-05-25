--------------------------------

% node -v
v18.20.2
% npm -v
6.11.3
% ng --version
Angular CLI: 8.3.0
 
PCにはinstall済みである
--------------------------------

ng new my-angular-app

--------------------------------

cd my-angular-app

export NODE_OPTIONS=--openssl-legacy-provider

ng serve

open your browser on 

http://localhost:4200/


--------------------------------

cd my-angular-app
ng generate component rate-contest

src/app/rate-contest/rate-contest.component.htmlを開き、提供されたHTMLコードを貼り付けます。

src/app/rate-contest/rate-contest.component.tsを開き、次のコードを追加します。

src/app/app.module.tsを開き、RateContestComponentをインポートしてimports配列に追加します。

最後に、src/app/app.component.htmlを開き、<app-rate-contest></app-rate-contest>と追加します。

既存のmy-angular-app内に新しいコンポーネントが統合されました。ng serveコマンドを実行して、アプリケーションを確認できます。
