# git-clone-testing

This repository is created for testing different git clone commands used in blog post.

## full clone:
```bash
git clone https://github.com/ShubhamOulkar/git-clone-testing.git full-clone
```

## Shallow clone : 
```bash
git clone --depth=1 https://github.com/ShubhamOulkar/git-clone-testing.git shallow-clone
```

## blobless clone : 
```bash
git clone --filter=blob:none  https://github.com/ShubhamOulkar/git-clone-testing.git blobless-clone
```

## treeless clone :
```bash
git clone --filter=tree:0  https://github.com/ShubhamOulkar/git-clone-testing.git treeless-clone
``` 
