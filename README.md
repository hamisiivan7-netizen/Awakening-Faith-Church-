import Navigation from "@/components/church/Navigation";
import EnhancedHero from "@/components/church/EnhancedHero";
import AboutSection from "@/components/church/AboutSection";
import MinistriesSection from "@/components/church/MinistriesSection";
import SermonsSection from "@/components/church/SermonsSection";
import EventsSection from "@/components/church/EventsSection";
import GiveSection from "@/components/church/GiveSection";
import ContactSection from "@/components/church/ContactSection";
import TestimonialsSection from "@/components/church/TestimonialsSection";
import EnhancedFooter from "@/components/church/EnhancedFooter";

const Index = () => {
  return (
    <>
      <Navigation />
      <main className="min-h-screen">
        <EnhancedHero />
        <AboutSection />
        <MinistriesSection />
        <SermonsSection />
        <EventsSection />
        <GiveSection />
        <TestimonialsSection />
        <ContactSection />
      </main>
      <EnhancedFooter />
    </>
  );
};

export default Index;
