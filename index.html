import React, { useState, useMemo } from 'react';
import { 
  ChefHat, 
  BookOpen, 
  GraduationCap, 
  Users, 
  ScrollText, 
  Utensils, 
  Calculator, 
  Award,
  ChevronRight,
  Menu,
  X,
  Search,
  CheckCircle2,
  Lock
} from 'lucide-react';

// --- Mock Data & Constants ---
const CATEGORIES = ['Hakka Heritage', 'Fine Gastronomy', 'Culinary Basics', 'Business Mastery'];

const RECIPES = [
  { id: 1, title: "Traditional Hakka Salt Baked Chicken", category: "Hakka Heritage", cost: 12.50, complexity: "Advanced", studentsOnly: false },
  { id: 2, title: "Modern Chinese Gastronomy Sauces", category: "Fine Gastronomy", cost: 8.20, complexity: "Professional", studentsOnly: true },
  { id: 3, title: "Restaurant Inventory Logic", category: "Business Mastery", cost: 0, complexity: "Intermediate", studentsOnly: true },
];

const EXAM_QUESTIONS = [
  {
    id: 1,
    question: "What is the primary heat-transfer method used in traditional Hakka wok cooking?",
    options: ["Convection", "Conduction", "Radiation", "Induction"],
    correct: 1
  },
  {
    id: 2,
    question: "In food costing, if the Total Food Cost is $10 and your target Food Cost % is 25%, what should the selling price be?",
    options: ["$25", "$35", "$40", "$50"],
    correct: 2
  }
];

// --- Components ---

const SidebarLink = ({ icon: Icon, label, active, onClick }) => (
  <button 
    onClick={onClick}
    className={`w-full flex items-center space-x-3 px-4 py-3 rounded-xl transition-all ${
      active 
        ? 'bg-amber-600 text-white shadow-lg shadow-amber-900/20' 
        : 'text-slate-400 hover:bg-slate-800 hover:text-white'
    }`}
  >
    <Icon size={20} />
    <span className="font-medium">{label}</span>
  </button>
);

const SectionHeader = ({ title, subtitle }) => (
  <div className="mb-8">
    <h2 className="text-3xl font-bold text-white mb-2">{title}</h2>
    <p className="text-slate-400">{subtitle}</p>
  </div>
);

// --- Main App ---

export default function App() {
  const [activeTab, setActiveTab] = useState('profile');
  const [isMobileMenuOpen, setIsMobileMenuOpen] = useState(false);
  const [examStarted, setExamStarted] = useState(false);
  const [examScore, setExamScore] = useState(null);
  const [searchQuery, setSearchQuery] = useState('');

  const filteredRecipes = useMemo(() => {
    return RECIPES.filter(r => 
      r.title.toLowerCase().includes(searchQuery.toLowerCase()) ||
      r.category.toLowerCase().includes(searchQuery.toLowerCase())
    );
  }, [searchQuery]);

  const renderContent = () => {
    switch (activeTab) {
      case 'profile':
        return (
          <div className="space-y-8 animate-in fade-in duration-500">
            <div className="relative h-64 rounded-3xl bg-gradient-to-r from-amber-600 to-orange-700 overflow-hidden shadow-2xl">
              <div className="absolute inset-0 bg-black/20" />
              <div className="absolute bottom-8 left-8 flex items-end space-x-6">
                <div className="w-32 h-32 rounded-2xl bg-white p-1 shadow-xl">
                  <div className="w-full h-full rounded-xl bg-slate-200 flex items-center justify-center">
                    <ChefHat size={48} className="text-amber-600" />
                  </div>
                </div>
                <div className="mb-2">
                  <h1 className="text-4xl font-bold text-white">Your Name</h1>
                  <p className="text-amber-100 font-medium">Executive Chef & Culinary Educator</p>
                </div>
              </div>
            </div>

            <div className="grid md:grid-cols-3 gap-6">
              <div className="md:col-span-2 space-y-6">
                <div className="bg-slate-900 border border-slate-800 p-8 rounded-3xl">
                  <h3 className="text-xl font-bold text-white mb-4">The Culinary Journey</h3>
                  <p className="text-slate-400 leading-relaxed">
                    With over 25 years of experience in the international culinary circuit, 
                    I specialize in Hakka Chinese Gastronomy and modern culinary education. 
                    From founding "Hakka Dhaka" to leading academic faculty, my mission is 
                    to preserve heritage through precision and logic.
                  </p>
                </div>
                
                <div className="grid grid-cols-2 gap-4">
                  <div className="bg-slate-900 border border-slate-800 p-6 rounded-3xl flex items-center space-x-4">
                    <div className="p-3 bg-amber-500/10 rounded-2xl text-amber-500">
                      <Award size={24} />
                    </div>
                    <div>
                      <div className="text-2xl font-bold text-white">25+</div>
                      <div className="text-xs text-slate-500 uppercase tracking-wider">Years Exp</div>
                    </div>
                  </div>
                  <div className="bg-slate-900 border border-slate-800 p-6 rounded-3xl flex items-center space-x-4">
                    <div className="p-3 bg-blue-500/10 rounded-2xl text-blue-500">
                      <Users size={24} />
                    </div>
                    <div>
                      <div className="text-2xl font-bold text-white">1.2k</div>
                      <div className="text-xs text-slate-500 uppercase tracking-wider">Students</div>
                    </div>
                  </div>
                </div>
              </div>

              <div className="space-y-6">
                <div className="bg-slate-900 border border-slate-800 p-6 rounded-3xl">
                  <h3 className="text-lg font-bold text-white mb-4">Core Expertise</h3>
                  <ul className="space-y-3">
                    {['Hakka Gastronomy', 'Kitchen Management', 'Recipe Costing', 'Curriculum Design'].map((skill) => (
                      <li key={skill} className="flex items-center space-x-2 text-slate-400">
                        <CheckCircle2 size={16} className="text-amber-500" />
                        <span>{skill}</span>
                      </li>
                    ))}
                  </ul>
                </div>
              </div>
            </div>
          </div>
        );

      case 'recipes':
        return (
          <div className="animate-in slide-in-from-bottom-4 duration-500">
            <SectionHeader 
              title="Culinary Library" 
              subtitle="Explore heritage recipes and professional food business tools." 
            />
            
            <div className="relative mb-8">
              <Search className="absolute left-4 top-1/2 -translate-y-1/2 text-slate-500" size={20} />
              <input 
                type="text" 
                placeholder="Search recipes, categories, or techniques..." 
                className="w-full bg-slate-900 border border-slate-800 rounded-2xl py-4 pl-12 pr-4 text-white focus:ring-2 focus:ring-amber-500 outline-none transition-all"
                value={searchQuery}
                onChange={(e) => setSearchQuery(e.target.value)}
              />
            </div>

            <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
              {filteredRecipes.map((recipe) => (
                <div key={recipe.id} className="group bg-slate-900 border border-slate-800 rounded-3xl overflow-hidden hover:border-amber-500/50 transition-all cursor-pointer">
                  <div className="h-48 bg-slate-800 relative">
                    <div className="absolute top-4 right-4 bg-black/60 backdrop-blur-md px-3 py-1 rounded-full text-xs font-bold text-amber-500 border border-amber-500/30">
                      {recipe.category}
                    </div>
                    {recipe.studentsOnly && (
                      <div className="absolute inset-0 flex items-center justify-center bg-black/40 backdrop-blur-[2px]">
                        <div className="flex items-center space-x-2 bg-slate-900 px-4 py-2 rounded-xl shadow-xl">
                          <Lock size={14} className="text-amber-500" />
                          <span className="text-xs font-bold text-white uppercase tracking-tighter">Student Only</span>
                        </div>
                      </div>
                    )}
                  </div>
                  <div className="p-6">
                    <h4 className="text-xl font-bold text-white mb-2 group-hover:text-amber-500 transition-colors">{recipe.title}</h4>
                    <div className="flex items-center justify-between text-slate-500 text-sm">
                      <div className="flex items-center space-x-1">
                        <Calculator size={14} />
                        <span>Est. Cost: ${recipe.cost.toFixed(2)}</span>
                      </div>
                      <span className="px-2 py-1 bg-slate-800 rounded text-xs">{recipe.complexity}</span>
                    </div>
                  </div>
                </div>
              ))}
            </div>
          </div>
        );

      case 'exam':
        return (
          <div className="max-w-3xl mx-auto animate-in fade-in duration-700">
            <SectionHeader 
              title="Culinary Examination" 
              subtitle="Test your professional knowledge and earn your digital endorsement." 
            />
            
            {!examStarted ? (
              <div className="bg-slate-900 border border-slate-800 p-10 rounded-[2.5rem] text-center space-y-6">
                <div className="w-20 h-20 bg-amber-500/10 rounded-3xl flex items-center justify-center mx-auto text-amber-500">
                  <ScrollText size={40} />
                </div>
                <h3 className="text-2xl font-bold text-white">Hakka Gastronomy Level 1</h3>
                <p className="text-slate-400">
                  This examination covers fundamental techniques, hygiene standards, 
                  and basic recipe logic. You need 80% to pass.
                </p>
                <div className="flex flex-col items-center space-y-4 pt-4">
                  <button 
                    onClick={() => setExamStarted(true)}
                    className="bg-amber-600 hover:bg-amber-500 text-white px-8 py-4 rounded-2xl font-bold transition-all w-full md:w-auto"
                  >
                    Begin Examination
                  </button>
                  <p className="text-xs text-slate-500 uppercase tracking-widest font-semibold italic">Requires active membership</p>
                </div>
              </div>
            ) : (
              <div className="space-y-6">
                {EXAM_QUESTIONS.map((q, idx) => (
                  <div key={q.id} className="bg-slate-900 border border-slate-800 p-8 rounded-3xl">
                    <p className="text-slate-500 text-sm mb-2">Question {idx + 1} of {EXAM_QUESTIONS.length}</p>
                    <h4 className="text-lg font-bold text-white mb-6">{q.question}</h4>
                    <div className="grid gap-3">
                      {q.options.map((opt, i) => (
                        <button key={i} className="text-left p-4 rounded-xl bg-slate-800 border border-slate-700 hover:border-amber-500/50 text-slate-300 hover:text-white transition-all">
                          {opt}
                        </button>
                      ))}
                    </div>
                  </div>
                ))}
                <button 
                  onClick={() => { setExamStarted(false); setExamScore(100); }}
                  className="w-full bg-slate-800 py-4 rounded-2xl text-slate-400 font-bold"
                >
                  Submit for Evaluation
                </button>
              </div>
            )}
          </div>
        );

      default:
        return null;
    }
  };

  return (
    <div className="min-h-screen bg-slate-950 text-slate-200 font-sans selection:bg-amber-500 selection:text-black">
      {/* Sidebar - Desktop */}
      <aside className="fixed left-0 top-0 h-full w-72 bg-slate-950 border-r border-slate-900 p-6 hidden lg:flex flex-col z-50">
        <div className="flex items-center space-x-3 mb-12 px-2">
          <div className="w-10 h-10 bg-amber-600 rounded-xl flex items-center justify-center text-white font-bold text-xl">H</div>
          <span className="font-bold text-xl text-white tracking-tight leading-none">HAKKA<br/><span className="text-xs uppercase text-amber-500">Professional</span></span>
        </div>

        <nav className="flex-1 space-y-2">
          <SidebarLink icon={ChefHat} label="Professional Bio" active={activeTab === 'profile'} onClick={() => setActiveTab('profile')} />
          <SidebarLink icon={Utensils} label="Recipes & Business" active={activeTab === 'recipes'} onClick={() => setActiveTab('recipes')} />
          <SidebarLink icon={GraduationCap} label="Culinary Academy" active={activeTab === 'exam'} onClick={() => setActiveTab('exam')} />
          <SidebarLink icon={BookOpen} label="Resource Library" active={activeTab === 'library'} onClick={() => setActiveTab('library')} />
          <SidebarLink icon={Users} label="Member Hub" active={activeTab === 'members'} onClick={() => setActiveTab('members')} />
        </nav>

        <div className="mt-auto">
          <div className="bg-slate-900/50 p-4 rounded-2xl border border-slate-800">
            <div className="flex items-center justify-between mb-2">
              <span className="text-xs font-bold text-slate-500 uppercase tracking-wider">Storage Usage</span>
              <span className="text-xs font-bold text-amber-500">65%</span>
            </div>
            <div className="h-1.5 w-full bg-slate-800 rounded-full overflow-hidden">
              <div className="h-full bg-amber-600 rounded-full" style={{ width: '65%' }} />
            </div>
            <p className="text-[10px] text-slate-500 mt-2 italic">Connected to Google Workspace</p>
          </div>
        </div>
      </aside>

      {/* Mobile Nav */}
      <div className="lg:hidden flex items-center justify-between p-4 bg-slate-950 border-b border-slate-900 sticky top-0 z-50">
        <div className="flex items-center space-x-2">
          <div className="w-8 h-8 bg-amber-600 rounded-lg flex items-center justify-center text-white font-bold">H</div>
          <span className="font-bold text-white tracking-tight">HAKKA</span>
        </div>
        <button onClick={() => setIsMobileMenuOpen(!isMobileMenuOpen)} className="p-2 text-slate-400">
          {isMobileMenuOpen ? <X size={24} /> : <Menu size={24} />}
        </button>
      </div>

      {/* Main Content Area */}
      <main className="lg:ml-72 min-h-screen p-4 md:p-8 lg:p-12 pb-24">
        <header className="flex flex-col md:flex-row md:items-center justify-between mb-12 gap-4">
          <div>
            <h2 className="text-slate-500 font-medium">Welcome back, Chef</h2>
            <p className="text-white text-xl font-bold">Manage your digital culinary empire</p>
          </div>
          <div className="flex items-center space-x-4">
            <button className="flex items-center space-x-2 bg-slate-900 border border-slate-800 px-4 py-2 rounded-xl text-slate-400 hover:text-white transition-all">
              <Lock size={16} />
              <span className="text-sm font-medium">Admin Dashboard</span>
            </button>
            <div className="w-10 h-10 rounded-full bg-amber-600 flex items-center justify-center text-white font-bold ring-4 ring-amber-600/10">
              C
            </div>
          </div>
        </header>

        {renderContent()}
      </main>

      {/* Quick Action Dock - Mobile Only */}
      <div className="fixed bottom-6 left-1/2 -translate-x-1/2 bg-slate-900/80 backdrop-blur-xl border border-white/10 px-6 py-3 rounded-3xl shadow-2xl flex items-center space-x-8 lg:hidden z-50">
        <button onClick={() => setActiveTab('profile')} className={`p-2 ${activeTab === 'profile' ? 'text-amber-500' : 'text-slate-500'}`}>
          <ChefHat size={24} />
        </button>
        <button onClick={() => setActiveTab('recipes')} className={`p-2 ${activeTab === 'recipes' ? 'text-amber-500' : 'text-slate-500'}`}>
          <Utensils size={24} />
        </button>
        <button onClick={() => setActiveTab('exam')} className={`p-2 ${activeTab === 'exam' ? 'text-amber-500' : 'text-slate-500'}`}>
          <GraduationCap size={24} />
        </button>
      </div>
    </div>
  );
}
