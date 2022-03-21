```typescript
import 

generatePng({
  type: 'match',
  sport: 'soccer',
  league: 'Leinster Senior League Senior Division',
  team1: {
    img: 'https://content.bookieratings.net/images/fq/tx/fqtxnf_20181001112329_100x100.png',
    name: 'Nizhny Novgorod'
  },
  team2: {
    img: 'https://content.bookieratings.net/images/fq/tx/fqtxnf_20181001112329_100x100.png',
    name: 'Lokomotiv Moscow'
  },
  date: '21.03.2022 8:00 UTC',
  betAmount: '100 USDC',
  outcome: 'Total Under(2.5)',
  betOdds: '2.88',
  currentOdds: '1.88'
}).then(buffer => {
  console.log(buffer);
})
```