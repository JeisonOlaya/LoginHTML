index

/* Media Queries */
@media only screen and (max-width: 1440px) {
    .img_logo {
        width: 600px;
        height: 600px;
    }
    
    .menu {
        font-size: 18px;
        gap: 25px;
    }
}

@media only screen and (max-width: 1024px) {
    .img_logo {
        width: 500px;
        height: 500px;
    }
    
    .header h1 {
        font-size: 28px;
    }
    
    .menu {
        font-size: 16px;
        gap: 20px;
    }
}

@media only screen and (max-width: 768px) {
    .img_logo {
        width: 400px;
        height: 400px;
    }
    
    .menu {
        flex-direction: column;
        gap: 15px;
        align-items: center;
    }
    
    .menu-link {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    
    .icon {
        margin-bottom: 5px;
    }
    
    .header {
        padding: 15px 5px;
    }
}

@media only screen and (max-width: 576px) {
    .img_logo {
        width: 300px;
        height: 300px;
    }
    
    .header h1 {
        font-size: 24px;
    }
    
    .menu {
        font-size: 14px;
    }
    
    .footer p {
        font-size: 14px;
        line-height: 1.5;
    }
}

@media only screen and (max-width: 400px) {
    .img_logo {
        width: 250px;
        height: 250px;
    }
    
    .header h1 {
        font-size: 20px;
    }
    
    .menu {
        font-size: 13px;
        gap: 10px;
    }
    
    .footer {
        padding: 15px 0;
    }
    
    .footer p {
        font-size: 12px;
    }
}
