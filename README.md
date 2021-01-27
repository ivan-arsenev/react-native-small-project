# Difference between pure install of expo 📀

## Commands 🖨

        yarn add eslint-config-react-native-wcandillon --dev
        expo install expo-asset expo-constants expo-font

## tsconfig.json

        {
        "compilerOptions": {
            "allowSyntheticDefaultImports": true,
            "jsx": "react-native",
            "lib": ["dom", "esnext"],
            "moduleResolution": "node",
            "noEmit": true,
            "skipLibCheck": true,
            "resolveJsonModule": true,
            "strict": true,
            "noImplicitAny": true,
            "strictNullChecks": true,
            "strictFunctionTypes": true,
            "strictPropertyInitialization": true,
            "noImplicitThis": true,
            "alwaysStrict": true,
            "noUnusedLocals": true,
            "noUnusedParameters": true,
            "noImplicitReturns": true,
            "noFallthroughCasesInSwitch": true,
            "forceConsistentCasingInFileNames": true
        }
        }

# package.json

        "lint": "eslint --ext .ts,.tsx .",
        "tsc": "tsc",
        "ci": "yarn lint && yarn tsc"
