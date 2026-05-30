import React from 'react';
import { Phone, Mail, MapPin, ShieldCheck, Cpu, Clock } from 'lucide-react';

export default function PremiumFooter() {
  return (
    <footer className="bg-[#0b111e] text-slate-300 border-t border-slate-800 pt-16 pb-8 font-sans">
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        
        {/* ÜST BÖLÜM: Büyütülmüş Devasa İkonlar ve Güven Çubukları */}
        <div className="grid grid-cols-1 md:grid-cols-3 gap-8 pb-12 border-b border-slate-800">
          <div className="flex items-center space-x-4">
            <div className="p-4 bg-blue-500/10 rounded-xl text-blue-500 border border-blue-500/20 shadow-[0_0_15px_rgba(59,130,246,0.1)]">
              <Cpu className="w-10 h-10" /> {/* İkon Boyutu Büyütüldü */}
            </div>
            <div>
              <h4 className="text-xl font-bold text-white">İleri Mühendislik</h4>
              <p className="text-sm text-slate-400">Üst düzey otomasyonlu endüstriyel sistemler.</p>
            </div>
          </div>

          <div className="flex items-center space-x-4">
            <div className="p-4 bg-blue-500/10 rounded-xl text-blue-500 border border-blue-500/20 shadow-[0_0_15px_rgba(59,130,246,0.1)]">
              <ShieldCheck className="w-10 h-10" />
            </div>
            <div>
              <h4 className="text-xl font-bold text-white">2 Yıl Kesintisiz Garanti</h4>
              <p className="text-sm text-slate-400">Tüm mekanik ve dijital kurulumlar koruma altında.</p>
            </div>
          </div>

          <div className="flex items-center space-x-4">
            <div className="p-4 bg-blue-500/10 rounded-xl text-blue-500 border border-blue-500/20 shadow-[0_0_15px_rgba(59,130,246,0.1)]">
              <Clock className="w-10 h-10" />
            </div>
            <div>
              <h4 className="text-xl font-bold text-white">7/24 Teknik Servis</h4>
              <p className="text-sm text-slate-400">Soğuk zincirin kırılmaması için anlık müdahale.</p>
            </div>
          </div>
        </div>

        {/* ORTA BÖLÜM: Büyük Logo, Menüler ve Doğrudan İletişim */}
        <div className="grid grid-cols-1 lg:grid-cols-4 gap-12 py-12">
          
          {/* 1. Sütun: Büyük Logo ve Şirket Tanımı */}
          <div className="lg:col-span-1 space-y-6">
            <div className="flex items-center space-x-3">
              {/* NexFrigo Logosu - İstediğiniz gibi daha büyük ve vurgulu */}
              <div className="text-3xl font-extrabold tracking-wider text-white flex items-center gap-2">
                <span className="text-blue-500">NEX</span>FRIGO
              </div>
            </div>
            <p className="text-sm text-slate-400 leading-relaxed">
              Endüstriyel iklimlendirme ve soğuk hava depoları alanında yüksek performanslı, enerji tasarruflu ve akıllı lojistik çözümler üreten teknoloji odaklı mühendislik firması.
            </p>
          </div>

          {/* 2. Sütun: Hızlı Navigasyon */}
          <div>
            <h3 className="text-white text-lg font-bold mb-6 tracking-wide uppercase text-sm border-l-2 border-blue-500 pl-3">
              Çözümlerimiz
            </h3>
            <ul className="space-y-3 text-sm">
              <li><a href="#kurulum" className="hover:text-blue-400 transition-colors">Soğuk Hava Deposu Kurulumu</a></li>
              <li><a href="#muhafaza" className="hover:text-blue-400 transition-colors">Donuk & Şok Muhafaza</a></li>
              <li><a href="#iklimlendirme" className="hover:text-blue-400 transition-colors">Endüstriyel İklimlendirme</a></li>
              <li><a href="#servis" className="hover:text-blue-400 transition-colors">Periyodik Bakım & Onarım</a></li>
            </ul>
          </div>

          {/* 3. Sütun: Kurumsal İletişim Detayları */}
          <div className="lg:col-span-2 space-y-6">
            <h3 className="text-white text-lg font-bold mb-2 tracking-wide uppercase text-sm border-l-2 border-blue-500 pl-3">
              Merkez & İletişim Bölümü
            </h3>
            <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
              <div className="space-y-4">
                <div className="flex items-start space-x-3 text-sm">
                  <MapPin className="w-5 h-5 text-blue-500 shrink-0 mt-0.5" />
                  <span>Başakşehir, İkitelli Organize Sanayi Bölgesi, İstanbul, Türkiye</span>
                </div>
                <div className="flex items-center space-x-3 text-sm">
                  <Mail className="w-5 h-5 text-blue-500" />
                  <a href="mailto:info@nexfrigo.com" className="hover:text-blue-400">info@nexfrigo.com</a>
                </div>
              </div>

              {/* Hızlı Destek Hattı - Büyük ve Vurgulu */}
              <div className="bg-slate-900/50 p-4 rounded-xl border border-slate-800 flex flex-col justify-center">
                <span className="text-xs text-slate-400 uppercase tracking-wider">Hızlı Proje & Teklif Hattı</span>
                <div className="flex items-center space-x-2 mt-1 text-white hover:text-blue-400 transition-colors">
                  <Phone className="w-5 h-5 text-blue-500" />
                  <span className="text-lg font-mono font-bold">+90 (551) xxx xx xx</span>
                </div>
              </div>
            </div>
          </div>

        </div>

        {/* ALT BÖLÜM: Telif ve Yasal Bilgiler */}
        <div className="border-t border-slate-800 pt-8 flex flex-col md:flex-row justify-between items-center text-xs text-slate-500">
          <p>© {new Date().getFullYear()} NexFrigo Industrial Air Conditioning. Tüm hakları saklıdır.</p>
          <div className="space-x-6 mt-4 md:mt-0">
            <a href="#gizlilik" className="hover:text-slate-400">Gizlilik Politikası</a>
            <a href="#sartlar" className="hover:text-slate-400">Kullanım Şartları</a>
          </div>
        </div>

      </div>
    </footer>
  );
}
