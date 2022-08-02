# ERC-721 강의자료

##
> ### #. 만든 메타마스크 네트워크를 Rinkeby로 변경 후 https://faucets.chain.link/rinkeby 들어가서 연결 후 testETH 받기

> 1. MyNFTs.sol 파일을 클릭해서 들어가고 그 안에 있는 내용을 전부 복사 ( 전부 드래그 하여 ctrl+c )

> 2. 다른 브라우저를 키고 https://remix.ethereum.org/ 들어가기

> 3. Workspace를 만들기 (이름은 자유)

> 4. contracts폴던 안에 (이름은 자유).sol 파일을 만들기

> 5. 만든 파일을 클릭하고 그 안에 복사했던 내용을 전부 붙어넣기

> 6. 다 붙여넣었으면 Window는 ctrl + s mac은 command + s 를 입력

> 7. 왼쪽에 돋보기아이콘 밑에 있는 아이콘을 클릭

> 8. 상단에 COMPILER를 클릭하여 버전을 0.8.7버전을 찾아 클릭하여 바꾸기

> 9. Compile (이름은 자유).sol 버튼을 클릭

> 10. 왼쪽 돋보기아이콘 2번째 밑에 있는 아이콘을 클릭

> 11. ENVIRONMENT 부분을 Injected Provider로 변경 후 CONTRACT 부분에 ERC721를 찾아 클릭

> 12. Depoly 버튼 옆에 밑화살표 클릭

> 13. NAME 은 NFT 이름 SYMBOL 은 NFT이름약자 를 설정 후 transact 클릭

> 14. ONTRACT를 클릭하고 (이름은 자유).sol 로 선택하고 Deploy 클릭

> 15. 맨밑에 Deployed Contracts 부분이 생기면 >화살표 를 클릭

> 16. mintNFT 를 선택해서 빈칸을 입력(recipient 는 '메타마스크 주소', tokenURI 에는 NFT화 시킬 이미지가 저장되어있는 '주소')

> 17. https://www.pinata.cloud/ 로 들어가서 회원가입하기.

> 18. 회원가입이 끝나면 Upload 버튼 클릭 File 을 클릭 Select a file 클릭(NFT화 할 이미지 클릭)

> 19. CID 부분을 클릭하여 복사

> 20. (이름은 자유).json을 만듬.(MyNFTs.sol 위에 있는 json 형식 파일 확인)

> 21. image 부분에 ipfs://(여기에 복사붙여넣기).

> 22. 다시 돌아와서 Upload 버튼 클릭 File 을 클릭 Select a file 클릭 (이름은 자유).json 파일 클릭.

> 23. json 파일의 CID를 복사해서 'tokenURI' 에 넣고 transact 버튼 클릭 (16번째 2번째 빈칸)

> 24. https://testnets.opensea.io/ 에 들어가서 메타마스크와 지갑연결을 하고 NFT가 정상적으로 발행된걸 확인.



