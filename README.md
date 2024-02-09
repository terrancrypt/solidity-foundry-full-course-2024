<div align="center">

<h1>Web3 Development, Smart Contract & Solidity Course </br> Powered By AI  </h1>
<strong>Học cách phát triển Smart Contract Solidity và các ứng dụng Web3 tương thích EVM</strong>
<p align="center">
    <br />
    <a href="https://cyfrin.io/">
        <img src=".github/images/poweredbycyfrinbluehigher.png" width="145" alt=""/></a>
<a href="https://updraft.cyfrin.io/courses/foundry">
        <img src=".github/images/coursebadge.png" width="242.3" alt=""/></a>
    <br />
</p>
Chào mừng bạn đến với repository của khoá học Web3 Development, Smart Contract & Solidity Course. Khoá học này được phát triển bởi <a href="https://cyfrin.io/">Cyfrin</a> và <a href="https://www.youtube.com/@PatrickAlphaC">Patrick Collins</a>, cập nhật, sửa đổi và dịch thuật sang tiếng Việt bởi <a href="https://www.youtube.com/channel/UC0QESw8LTPb841qcABmOsvA">Terran Crypt</a>.
</div>

# Foundry Full Course F23

Trong toàn bộ khoá học này, phần lớn kiến thức là đến từ khoá học Foundry Full Course F23 của Cyfrin's Updraft. Tuy nhiên sẽ có thay đổi để cập nhật kiến thức và dịch thuật, diễn đạt nội dung để phù hợp hơn với khán giả Việt Nam.

## Link gốc của khoá học
<br/>
<table>
  <tr>
    <th align="center">Lessons 0 - 6</th>
    <th align="center">Lessons 7 - 11</th>
    <th align="center">Lessons 12 - 15</th>
  </tr>
  <tr>
    <td align="center">
      <a href="https://youtu.be/umepbfKp5rI" target="_blank">
        <img src=".github/thumbnails/thumbnail-1.png" width="300" alt="Blockchain Developer, Smart Contract, & Solidity Course - Powered By AI 1">
      </a>
    </td>
    <td align="center">
      <a href="https://youtu.be/sas02qSFZ74" target="_blank">
        <img src=".github/thumbnails/thumbnail-2.png" width="300" alt="Blockchain Developer, Smart Contract, & Solidity Course - Powered By AI 2">
      </a>
    </td>
    <td align="center">
      <a href="https://youtu.be/wUjYK5gwNZs" target="_blank">
        <img src=".github/thumbnails/thumbnail-3.png" width="300" alt="Blockchain Developer, Smart Contract, & Solidity Course - Powered By AI 3">
      </a>
    </td>
  </tr>
</table>
<br/>

## Link content của Cyfrin

-   [Website](https://updraft.cyfrin.io) - Webside chính thức của Cyfrin's Updraft, nơi bạn có thể học rất nhiều khoá học từ cơ bản đến nâng cao về Smart Contract & Solidity.
-   [Twitter](https://x.com/CyfrinUpdraft) - Link X của Cyfrin để liên tục cập nhật thông tin.
-   [LinkedIn](https://www.linkedin.com/school/cyfrin-updraft/) - Linkedin của Cyfrin's Updraft
-   [Discord](https://discord.gg/cyfrin) - Trang Discord của Cyfrin
-   [Newsletter](https://cyfrin.io/newsletter) - Bản tin hàng tuần về bảo mật và mẹo hay cho việc phát triển hợp đồng thông minh
-   [Codehawks](https://codehawks.com) - Nền tảng cho các cuộc thi audit được phát triển bởi Cyfrin.

# Tài nguyên dành cho khoá học này
- Testnet: Sepolia.

> ⚠️ Tất cả code liên quan đến khóa học này chỉ nhằm mục đích demo. Tất cả chưa được audit và không được coi là đã sẵn sàng để đưa vào production.

## Testnet Faucets
- Faucet chính: https://sepoliafaucet.com
- Faucet backup: https://faucets.chain.link/sepolia

## AI
- ChatGPT: https://chat.openai.com
- Phind: https://www.phind.com
- Bard: https://bard.google.com

## Nơi đặt câu hỏi
- Github Discussion: https://github.com/terrancrypt/web3-solidity-course-2024/discussions
- Ethereum Stack Exchange: https://ethereum.stackexchange.com
- Peeranha: https://peeranha.io

# Phần 0: Giới thiệu

_[⭐️ Video #0: Introduce](https://www.youtube.com/watch?v=H0b-D_I05co)_

## Lời khuyên
- **Follow repository này.** Tất cả những gì liên quan đến khoá học đều nằm ở repo này và nó sẽ thay đổi theo thời gian, vì vậy để giúp cho quá trình tìm hiểu kiến thức tốt nhất bạn hãy follow repo này nhé.
- **Đặt câu hỏi.** Mình thường xuyên active trên Github nên câu hỏi của bạn đặt trong phần Discussion của Repo này mình sẽ có thể thấy và trả lời câu hỏi của bạn một cách thường xuyên nên đừng ngại đặt bất kỳ câu hỏi gì nếu cảm thấy bị vướng mắc.
- **Tìm kiếm tài liệu.** Ngoài dịch document của Patrick trong khoá học gốc sang tiếng Việt, mình cũng cố gắng tìm rất nhiều nguồn tài liệu khác. Mục đích để có nhiều tài nguyên nhất trong quá trình học tập của bạn. Nhưng sức người có hạn nên có thể có nhiều thiếu sót để hổng kiến thức, mong bạn nếu cảm thấy chưa đủ hãy tìm thêm.
- **Học theo nhịp độ của bạn.** Mỗi người có một tốc độ học hỏi và tìm hiểu kiến thức khác nhau. Đừng quá thúc ép bản thân, cũng đừng trì hoãn việc cần làm. Có thể bạn chỉ mất cỡ 1 tuần để hoàn thành khoá này, cũng có thể bạn sẽ mất cả tháng mới học xong và hiểu hết. Tất cả đều có quá trình của nó.
- **Nghỉ ngơi.** Có thể bạn sẽ kiệt sức nếu ngồi quá lâu một chỗ (hoặc bị trĩ), nên hãy nhớ nhắc bản thân nghỉ ngơi mỗi khi làm việc được một lúc. Có thể bạn sẽ muốn học theo phương pháp pomodoro được chia sẻ trong [video này](https://www.youtube.com/watch?v=vm_-taF_CRw).

<p align="right">(<a href="#table-of-contents">back to top</a>) ⬆️</p>

# Phần 1: Blockchain cơ bản

## Blockchain là gì? Và để làm gì?
- [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf)
  - [Satoshi Nakamoto](https://en.wikipedia.org/wiki/Satoshi_Nakamoto)
- [Bitcoin Whitepaper tiếng Việt](https://bitcoin.org/files/bitcoin-paper/bitcoin_vi.pdf)
- [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)
  - [Vitalik Buterin](https://en.wikipedia.org/wiki/Vitalik_Buterin)
- [What is a Smart Contract?](https://chain.link/education/smart-contracts)
- [Nick Szabo](https://en.wikipedia.org/wiki/Nick_Szabo)
- [Hybrid Smart Contracts](https://blog.chain.link/hybrid-smart-contracts-explained/)
- [Blockchain Oracles](https://betterprogramming.pub/what-is-a-blockchain-oracle-f5ccab8dbd72?source=friends_link&sk=d921a38466df8a9176ed8dd767d8c77d)
- [Terminology](https://connect.comptia.org/content/articles/blockchain-terminology)
- [Web3](https://en.wikipedia.org/wiki/Web3)
- [What is a blockchain](https://www.investopedia.com/terms/b/blockchain.asp)

Nếu bạn chưa hiểu lắm, có thể thao khảo thêm một số video về blockchain mà không chuyên sâu về khía cạnh kỹ thuật của nó trong các video mình tìm được dưới đây.
- [BlockChain - Xương sống của Bitcoin là gì? Hiểu rõ trong 5 phút](https://www.youtube.com/watch?v=GkQuk3XDYf8)
- [BLOCKCHAIN LÀ GÌ? | TheAlchemist | TIỀN TÀI](https://www.youtube.com/watch?v=6qnMpxfptNY)
- [Blockchain ứng dụng vào giải trí như thế nào? | VTV24](https://www.youtube.com/watch?v=wZtiDavuk_A)
- [Tiềm năng và cơ hội cho Blockchain Việt Nam | VTV24](https://www.youtube.com/watch?v=XuLDSNOH8HA)

## Mục đích của Smart Contract

- [Understanding Decentralized Data and Computation.](https://www.youtube.com/watch?v=06hXCX_jj2E) Xem để hiểu tại sao chúng ta làm tất cả những thứ này, về blockchain, smart contract và web3.
- [The Evolution of Smart Contracts and Cryptoeconomic Security.](https://www.youtube.com/watch?v=ufVyX7JDCgg)
- [Smart contracts - Simply Explained.](https://www.youtube.com/watch?v=ZE2HxTmxfrI) Giải thích đơn giản về smart contract

## Các lợi ích của Blockchain
- Phi tập trung
- Minh bạch & linh hoạt
- Tốc độ & hiệu quả
- Bảo mật & bất biến
- Loại bỏ rủi ro đối tác
- Thỏa thuận giảm thiểu sự tin cậy

## Smart Contract đã làm được những gì?
- DeFi
- DAOs
- NFTs

## Tạo giao dịch đầu tiên
- [Metamask Download Link](https://etherscan.io/)
  - [Private Key & Passphrase là gì?](https://coin98.net/private-key-passphrase-la-gi)
- [Etherscan](https://etherscan.io/)
- [Sepolia Etherscan](https://sepolia.etherscan.io/)
- [Sepolia Faucet](https://sepoliafaucet.com/)

## Blockchain hoạt động như thế nào?
- Hash là gì?
- Blockchain Demo Website
- [Into To Ethereum] (https://ethereum.org/en/developers/docs/intro-to-ethereum)

## Ký giao dịch
- Public & Private Key
- Layer 2 & Rollup
- Decentralized Blockchain Oracle

## Gas
- [Gas & Gas Fee](https://ethereum.org/en/developers/docs/gas)
- Wei, Gwei & Ether
- [Block Reward](https://www.investopedia.com/terms/b/block-reward.asp)
- Gas nâng cao:
  - [EIP 1559](https://www.youtube.com/watch?v=MGemhK9t44Q)
  - Gwei, Wei & ETH
  - [ETH Converter](https://eth-converter.com/)
- [Chạy node](https://geth.ethereum.org/docs/getting-started)

## Kiến thức nâng cao về Blockchain
- [Consensus](https://wiki.polkadot.network/docs/learn-consensus)
- [Proof of Stake](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos)
- [Proof of Work](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow)
- [Nakamoto Consesus](https://blockonomi.com/nakamoto-consensus/)


