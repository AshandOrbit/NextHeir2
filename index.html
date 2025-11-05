<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NextHeir - Digital Legacy Preservation | Element United</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- React and ReactDOM -->
    <script crossorigin src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
    
    <!-- Recharts -->
    <script src="https://unpkg.com/recharts@2.5.0/dist/Recharts.js"></script>
    
    <!-- Babel Standalone for JSX -->
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    
    <style>
        body {
            margin: 0;
            font-family: 'Georgia', 'Garamond', serif;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
            background: #FAF8F3;
        }
        .sans-font {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', sans-serif;
        }
    </style>
</head>
<body>
    <div id="root"></div>

    <script type="text/babel">
        const { useState } = React;
        const { LineChart, Line, BarChart, Bar, XAxis, YAxis, CartesianGrid, Tooltip, Legend, ResponsiveContainer } = Recharts;

        // Icons
        const Heart = ({ size = 20 }) => (
            <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2">
                <path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"></path>
            </svg>
        );

        const Users = ({ size = 20 }) => (
            <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2">
                <path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path>
                <circle cx="9" cy="7" r="4"></circle>
                <path d="M23 21v-2a4 4 0 0 0-3-3.87"></path>
                <path d="M16 3.13a4 4 0 0 1 0 7.75"></path>
            </svg>
        );

        const Briefcase = ({ size = 20 }) => (
            <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2">
                <rect x="2" y="7" width="20" height="14" rx="2" ry="2"></rect>
                <path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"></path>
            </svg>
        );

        const Building = ({ size = 20 }) => (
            <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2">
                <rect x="4" y="2" width="16" height="20" rx="2" ry="2"></rect>
                <path d="M9 22v-4h6v4"></path>
                <path d="M8 6h.01"></path>
                <path d="M16 6h.01"></path>
                <path d="M12 6h.01"></path>
                <path d="M12 10h.01"></path>
                <path d="M12 14h.01"></path>
                <path d="M16 10h.01"></path>
                <path d="M16 14h.01"></path>
                <path d="M8 10h.01"></path>
                <path d="M8 14h.01"></path>
            </svg>
        );

        const Shield = ({ size = 20 }) => (
            <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2">
                <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path>
            </svg>
        );

        const Gift = ({ size = 20 }) => (
            <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2">
                <polyline points="20 12 20 22 4 22 4 12"></polyline>
                <rect x="2" y="7" width="20" height="5"></rect>
                <line x1="12" y1="22" x2="12" y2="7"></line>
                <path d="M12 7H7.5a2.5 2.5 0 0 1 0-5C11 2 12 7 12 7z"></path>
                <path d="M12 7h4.5a2.5 2.5 0 0 0 0-5C13 2 12 7 12 7z"></path>
            </svg>
        );

        const Image = ({ size = 20 }) => (
            <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2">
                <rect x="3" y="3" width="18" height="18" rx="2" ry="2"></rect>
                <circle cx="8.5" cy="8.5" r="1.5"></circle>
                <polyline points="21 15 16 10 5 21"></polyline>
            </svg>
        );

        const FileText = ({ size = 20 }) => (
            <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2">
                <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path>
                <polyline points="14 2 14 8 20 8"></polyline>
                <line x1="16" y1="13" x2="8" y2="13"></line>
                <line x1="16" y1="17" x2="8" y2="17"></line>
                <polyline points="10 9 9 9 8 9"></polyline>
            </svg>
        );

        const CheckCircle = ({ size = 16 }) => (
            <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2">
                <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
                <polyline points="22 4 12 14.01 9 11.01"></polyline>
            </svg>
        );

        const Plus = ({ size = 20 }) => (
            <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2">
                <line x1="12" y1="5" x2="12" y2="19"></line>
                <line x1="5" y1="12" x2="19" y2="12"></line>
            </svg>
        );

        const NextHeirDashboard = () => {
            const [activeRole, setActiveRole] = useState('family');
            const [activeTab, setActiveTab] = useState('vault');

            // Warm, luxury color palette
            const colors = {
                primary: '#D4AF37', // Warm gold
                secondary: '#C9A961', // Lighter gold
                cream: '#FAF8F3',
                warmGray: '#5A5A5A',
                darkGray: '#3E3E3E',
                rose: '#D4A5A5',
                success: '#7D9B76',
                elementYellow: '#E8FF00'
            };

            const roles = [
                { id: 'family', label: 'Individual/Family', icon: Heart },
                { id: 'attorney', label: 'Estate Attorney', icon: Briefcase },
                { id: 'museum', label: 'Museum/Collector', icon: Building },
                { id: 'insurance', label: 'Insurance Agent', icon: Shield },
                { id: 'brand', label: 'Luxury Brand', icon: FileText },
                { id: 'wedding', label: 'Weddings', icon: Gift }
            ];

            const heirlooms = [
                {
                    id: 'H001',
                    name: "Grandmother's Diamond Ring",
                    category: 'Jewelry',
                    value: '$12,500',
                    year: '1947',
                    memories: 8,
                    image: '💍'
                },
                {
                    id: 'H002',
                    name: 'Family Home - Brooklyn',
                    category: 'Real Estate',
                    value: '$1.2M',
                    year: '1965',
                    memories: 24,
                    image: '🏠'
                },
                {
                    id: 'H003',
                    name: 'Wedding China Collection',
                    category: 'Heirloom',
                    value: '$3,200',
                    year: '1952',
                    memories: 12,
                    image: '🍽️'
                },
                {
                    id: 'H004',
                    name: "Father's Watch - Omega",
                    category: 'Timepiece',
                    value: '$8,900',
                    year: '1978',
                    memories: 6,
                    image: '⌚'
                }
            ];

            const valueData = [
                { month: 'Jan', value: 1150 },
                { month: 'Feb', value: 1180 },
                { month: 'Mar', value: 1195 },
                { month: 'Apr', value: 1210 },
                { month: 'May', value: 1225 },
                { month: 'Jun', value: 1247 }
            ];

            const packages = [
                {
                    name: 'Keepsake',
                    price: '$29',
                    period: 'one-time',
                    description: 'One memory that matters',
                    features: [
                        '1 Digital Certificate',
                        'Photo & Document Upload',
                        'Basic Story Template',
                        'Share with 3 People',
                        'Permanent Storage'
                    ],
                    cta: 'Get Started'
                },
                {
                    name: 'Legacy Collection',
                    price: '$99',
                    period: 'one-time',
                    description: 'Curated family collection',
                    popular: true,
                    features: [
                        '10 Digital Certificates',
                        'Photo, Video & Audio Upload',
                        'Custom Story Templates',
                        'Share with 10 People',
                        'Family Tree Integration',
                        'Email Support'
                    ],
                    cta: 'Most Popular'
                },
                {
                    name: 'Archive Collection',
                    price: '$249',
                    period: 'one-time',
                    description: 'Build your digital archive',
                    features: [
                        '50 Digital Certificates',
                        'Unlimited Media Upload',
                        'Professional Story Support',
                        'Share with Unlimited People',
                        'Provenance Timeline',
                        'Priority Support',
                        'Estate Planning Tools'
                    ],
                    cta: 'Start Archiving'
                },
                {
                    name: 'Estate Collection',
                    price: '$499',
                    period: 'one-time',
                    description: 'Complete generational vault',
                    features: [
                        'Unlimited Certificates',
                        'Concierge Service',
                        'White-Glove Onboarding',
                        'Attorney Portal Access',
                        'Custom Templates',
                        'Video Storytelling',
                        'API Access',
                        'Dedicated Account Manager'
                    ],
                    cta: 'Contact Sales'
                }
            ];

            const addOns = [
                { name: 'Professional Story Writing', price: '$199', icon: '📝' },
                { name: 'Video Recording Session', price: '$299', icon: '🎥' },
                { name: 'Custom Certificate Design', price: '$149', icon: '🎨' },
                { name: 'Appraisal Integration', price: '$99', icon: '💎' },
                { name: 'Family Tree Mapping', price: '$179', icon: '🌳' }
            ];

            const getMetrics = () => {
                switch(activeRole) {
                    case 'family':
                        return [
                            { label: 'Items Preserved', value: '24', icon: '🏛️' },
                            { label: 'Memories Attached', value: '87', icon: '💭' },
                            { label: 'Family Members', value: '8', icon: '👨‍👩‍👧‍👦' },
                            { label: 'Total Value', value: '$1.2M', icon: '💰' }
                        ];
                    case 'attorney':
                        return [
                            { label: 'Client Estates', value: '45', icon: '📋' },
                            { label: 'Assets Documented', value: '892', icon: '📄' },
                            { label: 'Active Cases', value: '12', icon: '⚖️' },
                            { label: 'Settlement Ready', value: '8', icon: '✅' }
                        ];
                    case 'museum':
                        return [
                            { label: 'Collection Items', value: '3,421', icon: '🏛️' },
                            { label: 'Verified Provenance', value: '98%', icon: '✓' },
                            { label: 'On Display', value: '287', icon: '🖼️' },
                            { label: 'Total Value', value: '$45M', icon: '💎' }
                        ];
                    case 'insurance':
                        return [
                            { label: 'Active Policies', value: '234', icon: '🛡️' },
                            { label: 'Verified Assets', value: '1,456', icon: '✓' },
                            { label: 'Claims Processed', value: '18', icon: '📋' },
                            { label: 'Coverage Total', value: '$12M', icon: '💰' }
                        ];
                    case 'brand':
                        return [
                            { label: 'Products Certified', value: '8,942', icon: '💍' },
                            { label: 'Active Certificates', value: '8,129', icon: '📜' },
                            { label: 'Customer Trust', value: '4.9/5', icon: '⭐' },
                            { label: 'Return Rate', value: '0.3%', icon: '📊' }
                        ];
                    case 'wedding':
                        return [
                            { label: 'Couples Served', value: '347', icon: '💑' },
                            { label: 'Gifts Registered', value: '4,289', icon: '🎁' },
                            { label: 'Legacy Items', value: '892', icon: '💍' },
                            { label: 'Avg. Gift Value', value: '$2,400', icon: '💝' }
                        ];
                    default:
                        return [];
                }
            };

            return (
                <div className="min-h-screen" style={{ backgroundColor: colors.cream }}>
                    {/* Header */}
                    <div className="bg-white border-b" style={{ borderColor: '#E8E3D8' }}>
                        <div className="max-w-7xl mx-auto px-6 py-4">
                            <div className="flex items-center justify-between">
                                <div className="flex items-center space-x-3">
                                    <svg width="36" height="36" viewBox="0 0 100 100" fill="none">
                                        <path d="M50 5 L90 27.5 L90 72.5 L50 95 L10 72.5 L10 27.5 Z" 
                                              stroke={colors.primary} strokeWidth="3" fill="none"/>
                                        <circle cx="50" cy="50" r="15" stroke={colors.primary} strokeWidth="3" fill="none"/>
                                        <circle cx="50" cy="50" r="8" fill={colors.primary}/>
                                    </svg>
                                    <div>
                                        <h1 className="text-2xl font-semibold" style={{ color: colors.darkGray }}>NextHeir</h1>
                                        <p className="text-xs" style={{ color: colors.warmGray }}>Digital Legacy Preservation</p>
                                    </div>
                                </div>
                                <nav className="flex space-x-1 sans-font">
                                    {['vault', 'services', 'packages', 'partner'].map(tab => (
                                        <button
                                            key={tab}
                                            onClick={() => setActiveTab(tab)}
                                            className={`px-4 py-2 text-sm font-medium rounded-lg transition-colors ${
                                                activeTab === tab ? 'text-white' : 'hover:bg-gray-50'
                                            }`}
                                            style={{
                                                backgroundColor: activeTab === tab ? colors.primary : 'transparent',
                                                color: activeTab === tab ? 'white' : colors.warmGray
                                            }}
                                        >
                                            {tab.charAt(0).toUpperCase() + tab.slice(1)}
                                        </button>
                                    ))}
                                </nav>
                            </div>
                        </div>
                    </div>

                    {/* Role Selector */}
                    <div className="bg-white border-b" style={{ borderColor: '#E8E3D8' }}>
                        <div className="max-w-7xl mx-auto px-6 py-3">
                            <div className="flex items-center space-x-2 sans-font">
                                <span className="text-sm" style={{ color: colors.warmGray }}>View as:</span>
                                <div className="flex flex-wrap gap-2">
                                    {roles.map(role => {
                                        const Icon = role.icon;
                                        return (
                                            <button
                                                key={role.id}
                                                onClick={() => setActiveRole(role.id)}
                                                className={`flex items-center space-x-2 px-3 py-1.5 text-sm font-medium rounded-full transition-all ${
                                                    activeRole === role.id ? 'text-white' : 'hover:bg-gray-50'
                                                }`}
                                                style={{
                                                    backgroundColor: activeRole === role.id ? colors.primary : '#F5F3EE',
                                                    color: activeRole === role.id ? 'white' : colors.warmGray
                                                }}
                                            >
                                                <Icon size={14} />
                                                <span>{role.label}</span>
                                            </button>
                                        );
                                    })}
                                </div>
                            </div>
                        </div>
                    </div>

                    {/* Main Content */}
                    <div className="max-w-7xl mx-auto px-6 py-8">
                        
                        {/* Vault View */}
                        {activeTab === 'vault' && (
                            <div className="space-y-6">
                                {/* Metrics */}
                                <div className="grid grid-cols-4 gap-6 sans-font">
                                    {getMetrics().map((metric, idx) => (
                                        <div key={idx} className="bg-white rounded-xl p-6 border" style={{ borderColor: '#E8E3D8' }}>
                                            <div className="flex items-center justify-between mb-2">
                                                <span className="text-2xl">{metric.icon}</span>
                                            </div>
                                            <div className="text-sm mb-1" style={{ color: colors.warmGray }}>{metric.label}</div>
                                            <div className="text-2xl font-semibold" style={{ color: colors.darkGray }}>{metric.value}</div>
                                        </div>
                                    ))}
                                </div>

                                {/* Collection Grid */}
                                {activeRole === 'family' && (
                                    <>
                                        <div className="flex items-center justify-between">
                                            <h2 className="text-2xl font-semibold" style={{ color: colors.darkGray }}>Your Collection</h2>
                                            <button className="flex items-center space-x-2 px-4 py-2 rounded-lg text-white sans-font font-medium hover:opacity-90" style={{ backgroundColor: colors.primary }}>
                                                <Plus size={18} />
                                                <span>Add Heirloom</span>
                                            </button>
                                        </div>

                                        <div className="grid grid-cols-4 gap-6">
                                            {heirlooms.map(item => (
                                                <div key={item.id} className="bg-white rounded-xl overflow-hidden border hover:shadow-lg transition-shadow" style={{ borderColor: '#E8E3D8' }}>
                                                    <div className="h-48 flex items-center justify-center text-6xl" style={{ backgroundColor: '#F5F3EE' }}>
                                                        {item.image}
                                                    </div>
                                                    <div className="p-4">
                                                        <h3 className="font-semibold mb-1" style={{ color: colors.darkGray }}>{item.name}</h3>
                                                        <div className="text-xs mb-2" style={{ color: colors.warmGray }}>{item.category} • {item.year}</div>
                                                        <div className="flex items-center justify-between text-sm sans-font">
                                                            <span className="font-semibold" style={{ color: colors.primary }}>{item.value}</span>
                                                            <span style={{ color: colors.warmGray }}>{item.memories} memories</span>
                                                        </div>
                                                    </div>
                                                </div>
                                            ))}
                                        </div>

                                        {/* Value Chart */}
                                        <div className="bg-white rounded-xl p-6 border" style={{ borderColor: '#E8E3D8' }}>
                                            <h3 className="text-lg font-semibold mb-4" style={{ color: colors.darkGray }}>Collection Value Over Time</h3>
                                            <ResponsiveContainer width="100%" height={240}>
                                                <LineChart data={valueData}>
                                                    <CartesianGrid strokeDasharray="3 3" stroke="#E8E3D8" />
                                                    <XAxis dataKey="month" stroke={colors.warmGray} />
                                                    <YAxis stroke={colors.warmGray} />
                                                    <Tooltip />
                                                    <Line type="monotone" dataKey="value" stroke={colors.primary} strokeWidth={3} dot={{ fill: colors.primary }} />
                                                </LineChart>
                                            </ResponsiveContainer>
                                        </div>
                                    </>
                                )}
                            </div>
                        )}

                        {/* Services & Add-ons */}
                        {activeTab === 'services' && (
                            <div className="space-y-8">
                                <div className="text-center max-w-2xl mx-auto mb-8">
                                    <h2 className="text-3xl font-semibold mb-3" style={{ color: colors.darkGray }}>Services & Add-ons</h2>
                                    <p className="text-lg" style={{ color: colors.warmGray }}>
                                        Enhance your legacy with professional storytelling, video recording, and custom design
                                    </p>
                                </div>

                                <div className="grid grid-cols-3 gap-6 sans-font">
                                    {addOns.map((addon, idx) => (
                                        <div key={idx} className="bg-white rounded-xl p-6 border hover:shadow-lg transition-shadow" style={{ borderColor: '#E8E3D8' }}>
                                            <div className="text-4xl mb-4">{addon.icon}</div>
                                            <h3 className="text-lg font-semibold mb-2" style={{ color: colors.darkGray }}>{addon.name}</h3>
                                            <div className="text-2xl font-bold mb-4" style={{ color: colors.primary }}>{addon.price}</div>
                                            <button className="w-full py-2 rounded-lg font-medium transition-colors" style={{ 
                                                backgroundColor: colors.primary,
                                                color: 'white'
                                            }}>
                                                Add to Package
                                            </button>
                                        </div>
                                    ))}
                                </div>

                                {/* Additional Services */}
                                <div className="bg-white rounded-xl p-8 border text-center" style={{ borderColor: '#E8E3D8' }}>
                                    <h3 className="text-2xl font-semibold mb-3" style={{ color: colors.darkGray }}>
                                        Enterprise & Custom Solutions
                                    </h3>
                                    <p className="text-lg mb-6" style={{ color: colors.warmGray }}>
                                        Need something more? We offer white-label solutions, API access, and custom development for enterprises.
                                    </p>
                                    <button className="px-8 py-3 rounded-lg font-medium sans-font" style={{ 
                                        backgroundColor: colors.darkGray,
                                        color: 'white'
                                    }}>
                                        Contact Enterprise Team
                                    </button>
                                </div>
                            </div>
                        )}

                        {/* Packages */}
                        {activeTab === 'packages' && (
                            <div className="space-y-8">
                                <div className="text-center max-w-2xl mx-auto mb-8">
                                    <h2 className="text-3xl font-semibold mb-3" style={{ color: colors.darkGray }}>Choose Your Legacy Package</h2>
                                    <p className="text-lg" style={{ color: colors.warmGray }}>
                                        One-time purchase. Lifetime preservation. No subscriptions.
                                    </p>
                                </div>

                                <div className="grid grid-cols-4 gap-6 sans-font">
                                    {packages.map((pkg, idx) => (
                                        <div 
                                            key={idx} 
                                            className={`bg-white rounded-xl p-6 border-2 ${pkg.popular ? 'ring-4' : ''}`}
                                            style={{ 
                                                borderColor: pkg.popular ? colors.primary : '#E8E3D8',
                                                ringColor: pkg.popular ? colors.secondary : 'transparent'
                                            }}
                                        >
                                            {pkg.popular && (
                                                <div className="text-xs font-bold mb-2 px-2 py-1 rounded inline-block" style={{ 
                                                    backgroundColor: colors.primary,
                                                    color: 'white'
                                                }}>
                                                    MOST POPULAR
                                                </div>
                                            )}
                                            <h3 className="text-xl font-bold mb-1" style={{ color: colors.darkGray }}>{pkg.name}</h3>
                                            <p className="text-sm mb-4" style={{ color: colors.warmGray }}>{pkg.description}</p>
                                            <div className="mb-6">
                                                <span className="text-3xl font-bold" style={{ color: colors.primary }}>{pkg.price}</span>
                                                <span className="text-sm ml-1" style={{ color: colors.warmGray }}>/{pkg.period}</span>
                                            </div>
                                            <ul className="space-y-3 mb-6">
                                                {pkg.features.map((feature, fidx) => (
                                                    <li key={fidx} className="flex items-start space-x-2 text-sm">
                                                        <CheckCircle size={16} style={{ color: colors.success, minWidth: '16px', marginTop: '2px' }} />
                                                        <span style={{ color: colors.warmGray }}>{feature}</span>
                                                    </li>
                                                ))}
                                            </ul>
                                            <button className="w-full py-3 rounded-lg font-medium" style={{ 
                                                backgroundColor: pkg.popular ? colors.primary : colors.darkGray,
                                                color: 'white'
                                            }}>
                                                {pkg.cta}
                                            </button>
                                        </div>
                                    ))}
                                </div>

                                <div className="bg-white rounded-xl p-6 border text-center" style={{ borderColor: '#E8E3D8' }}>
                                    <p className="text-sm" style={{ color: colors.warmGray }}>
                                        <strong>First 250 customers receive 20% off</strong> all packages. Use code <strong style={{ color: colors.primary }}>LEGACY20</strong> at checkout.
                                    </p>
                                </div>
                            </div>
                        )}

                        {/* Partner */}
                        {activeTab === 'partner' && (
                            <div className="space-y-8">
                                <div className="text-center max-w-2xl mx-auto mb-8">
                                    <h2 className="text-3xl font-semibold mb-3" style={{ color: colors.darkGray }}>Partner With NextHeir</h2>
                                    <p className="text-lg" style={{ color: colors.warmGray }}>
                                        Join our network of trusted professionals, vendors, and enterprises
                                    </p>
                                </div>

                                <div className="grid grid-cols-3 gap-6 sans-font">
                                    <div className="bg-white rounded-xl p-8 border text-center hover:shadow-lg transition-shadow" style={{ borderColor: '#E8E3D8' }}>
                                        <div className="text-5xl mb-4">🤝</div>
                                        <h3 className="text-xl font-bold mb-3" style={{ color: colors.darkGray }}>Become a Vendor</h3>
                                        <p className="mb-6" style={{ color: colors.warmGray }}>
                                            Appraisers, photographers, attorneys, and estate professionals
                                        </p>
                                        <button className="px-6 py-3 rounded-lg font-medium" style={{ 
                                            backgroundColor: colors.primary,
                                            color: 'white'
                                        }}>
                                            Apply Now
                                        </button>
                                    </div>

                                    <div className="bg-white rounded-xl p-8 border text-center hover:shadow-lg transition-shadow" style={{ borderColor: '#E8E3D8' }}>
                                        <div className="text-5xl mb-4">🏢</div>
                                        <h3 className="text-xl font-bold mb-3" style={{ color: colors.darkGray }}>Enterprise Solutions</h3>
                                        <p className="mb-6" style={{ color: colors.warmGray }}>
                                            White-label, API access, volume licensing for institutions
                                        </p>
                                        <button className="px-6 py-3 rounded-lg font-medium" style={{ 
                                            backgroundColor: colors.darkGray,
                                            color: 'white'
                                        }}>
                                            Request Demo
                                        </button>
                                    </div>

                                    <div className="bg-white rounded-xl p-8 border text-center hover:shadow-lg transition-shadow" style={{ borderColor: '#E8E3D8' }}>
                                        <div className="text-5xl mb-4">📈</div>
                                        <h3 className="text-xl font-bold mb-3" style={{ color: colors.darkGray }}>Investment Opportunities</h3>
                                        <p className="mb-6" style={{ color: colors.warmGray }}>
                                            Join our journey to preserve the world's legacy
                                        </p>
                                        <button className="px-6 py-3 rounded-lg font-medium" style={{ 
                                            backgroundColor: colors.darkGray,
                                            color: 'white'
                                        }}>
                                            Learn More
                                        </button>
                                    </div>
                                </div>

                                {/* Testimonials */}
                                <div className="bg-white rounded-xl p-8 border" style={{ borderColor: '#E8E3D8' }}>
                                    <h3 className="text-2xl font-semibold mb-6 text-center" style={{ color: colors.darkGray }}>
                                        Trusted by Professionals
                                    </h3>
                                    <div className="grid grid-cols-2 gap-8">
                                        <div className="space-y-3">
                                            <p className="italic" style={{ color: colors.warmGray }}>
                                                "NextHeir has transformed how I handle estate documentation. My clients love having permanent digital records."
                                            </p>
                                            <div>
                                                <div className="font-semibold" style={{ color: colors.darkGray }}>Sarah Chen, Esq.</div>
                                                <div className="text-sm" style={{ color: colors.warmGray }}>Estate Planning Attorney</div>
                                            </div>
                                        </div>
                                        <div className="space-y-3">
                                            <p className="italic" style={{ color: colors.warmGray }}>
                                                "As a luxury jeweler, providing blockchain certificates has become our competitive advantage. Clients expect it now."
                                            </p>
                                            <div>
                                                <div className="font-semibold" style={{ color: colors.darkGray }}>Marcus Delacroix</div>
                                                <div className="text-sm" style={{ color: colors.warmGray }}>Fine Jewelry Atelier</div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        )}

                    </div>

                    {/* Footer */}
                    <div className="bg-white border-t mt-12" style={{ borderColor: '#E8E3D8' }}>
                        <div className="max-w-7xl mx-auto px-6 py-8 text-center">
                            <p className="text-sm italic" style={{ color: colors.warmGray }}>
                                Every element tells a story. Element United built the system that maps them all—making trust infrastructure.
                            </p>
                        </div>
                    </div>
                </div>
            );
        };

        // Render
        ReactDOM.render(<NextHeirDashboard />, document.getElementById('root'));
    </script>
</body>
</html>
