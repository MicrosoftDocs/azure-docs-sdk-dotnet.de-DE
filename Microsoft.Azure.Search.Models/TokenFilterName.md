<Type Name="TokenFilterName" FullName="Microsoft.Azure.Search.Models.TokenFilterName">
  <TypeSignature Language="C#" Value="public sealed class TokenFilterName : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TokenFilterName extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.TokenFilterName" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TokenFilterName&#xA;Inherits ExtensibleEnum(Of TokenFilterName)" />
  <TypeSignature Language="F#" Value="type TokenFilterName = class&#xA;    inherit ExtensibleEnum&lt;TokenFilterName&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.TokenFilterName</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Definiert die Namen aller token Filter, die von Azure Search unterstützt.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Custom-analyzers-in-Azure-Search" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Apostrophe">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Apostrophe;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Apostrophe" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Apostrophe" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Apostrophe As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Apostrophe : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Apostrophe" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Entfernt alle Zeichen nach einem Apostroph (einschließlich des Apostrophs).
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/tr/ApostropheFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ArabicNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName ArabicNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName ArabicNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.ArabicNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly ArabicNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable ArabicNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.ArabicNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ein token Filter, der die arabische Normalisierungsfunktion zum Normalisieren der Orthography gilt.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ar/ArabicNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsciiFolding">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName AsciiFolding;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName AsciiFolding" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.AsciiFolding" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly AsciiFolding As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable AsciiFolding : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.AsciiFolding" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alphabetische, numerische und symbolische Unicode-Zeichen, die nicht in der ersten 127 ASCII-Zeichen ("Lateinischen" Unicode-Block) sind konvertiert in ihre ASCII-Entsprechungen, wenn solche Entsprechungen vorhanden sind.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/ASCIIFoldingFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CjkBigram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName CjkBigram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName CjkBigram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.CjkBigram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly CjkBigram As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable CjkBigram : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.CjkBigram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Formulare digramme CJK-Begriffe, die von StandardTokenizer generiert werden.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/cjk/CJKBigramFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CjkWidth">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName CjkWidth;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName CjkWidth" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.CjkWidth" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly CjkWidth As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable CjkWidth : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.CjkWidth" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Normalisiert abweichungen bei der Zeichenbreite CJK-Schriftarten. Falten voller ASCII-Varianten in die entsprechende grundlegenden lateinischen und halbe Breite Katakana-Varianten in die entsprechende Kana.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/cjk/CJKWidthFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Classic">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Classic;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Classic" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Classic" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Classic As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Classic : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Classic" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Englische Possessivformen entfernt, und Punkte aus Akronyme.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/standard/ClassicFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonGram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName CommonGram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName CommonGram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.CommonGram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly CommonGram As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable CommonGram : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.CommonGram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erstellen Sie digramme für häufig auftretende Begriffe beim indizieren.
            Einzelne Ausdrücke sind, weiterhin mit digramme Überlagerung indiziert.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/commongrams/CommonGramsFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.TokenFilterName Create (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.TokenFilterName Create(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenFilterName.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (name As String) As TokenFilterName" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Create name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Filters token.</param>
        <summary>
            Erstellt eine neue Instanz der TokenFilterName oder eine vorhandene Instanz zurück, wenn dem angegebenen Namen, die von einem bekannten token Filter übereinstimmt.
            </summary>
        <returns>Eine TokenFilterName-Instanz mit dem angegebenen Namen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EdgeNGram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName EdgeNGram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName EdgeNGram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.EdgeNGram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly EdgeNGram As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable EdgeNGram : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.EdgeNGram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            N-gramme richtet, der den angegebenen VM-Größe(n) ab Anfang oder Ende ein Eingabetoken wird generiert.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/EdgeNGramTokenFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Elision">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Elision;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Elision" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Elision" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Elision As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Elision : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Elision" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Entfernt auslassungen. Beispielsweise wird "l'avion" (Ebene) in "Avion" (Ebene) konvertiert werden.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/util/ElisionFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GermanNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName GermanNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName GermanNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.GermanNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly GermanNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable GermanNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.GermanNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Normalisiert die deutsche Zeichen gemäß der Heuristik des German2 Snowball-Algorithmus.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/de/GermanNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HindiNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName HindiNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName HindiNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.HindiNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly HindiNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable HindiNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.HindiNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Normalisiert Text in Hindi So entfernen Sie einige Unterschiede bei Rechtschreibvariationen.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/hi/HindiNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndicNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName IndicNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName IndicNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.IndicNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly IndicNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable IndicNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.IndicNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Normalisiert die Unicode-Darstellung von Text in indischen Sprachen.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/in/IndicNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeywordRepeat">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName KeywordRepeat;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName KeywordRepeat" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.KeywordRepeat" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly KeywordRepeat As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable KeywordRepeat : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.KeywordRepeat" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt jedes eingehende Token zweimal einmal as-Schlüsselwort und einmal als nicht-Schlüsselwort.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/KeywordRepeatFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KStem">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName KStem;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName KStem" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.KStem" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly KStem As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable KStem : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.KStem" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eine hohe Leistung Kstem Filter für Englisch.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/en/KStemFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Length;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Length" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Length" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Length As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Length : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Length" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Entfernt ein Wort, die zu lang oder zu kurz sind.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/LengthFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Limit;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Limit" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Limit As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Limit : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Limit" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Schränkt die Anzahl der Token beim indizieren.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/LimitTokenCountFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lowercase">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Lowercase;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Lowercase" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Lowercase" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Lowercase As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Lowercase : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Lowercase" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Normalisiert die token-Text in Kleinbuchstaben umgewandelt.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/LowerCaseFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NGram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName NGram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName NGram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.NGram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly NGram As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable NGram : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.NGram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            N-gramme richtet, der den angegebenen VM-Größe(n) wird generiert.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/NGramTokenFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.TokenFilterName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.TokenFilterName op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenFilterName.op_Implicit(System.String)~Microsoft.Azure.Search.Models.TokenFilterName" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As TokenFilterName" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">zu konvertierende Zeichenfolge.</param>
        <summary>
            Definiert die implizite Konvertierung von Zeichenfolgen in TokenFilterName.
            </summary>
        <returns>Die Zeichenfolge als eine TokenFilterName.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PersianNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName PersianNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName PersianNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.PersianNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly PersianNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable PersianNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.PersianNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gilt für Persisch Normalisierung.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/fa/PersianNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Phonetic">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Phonetic;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Phonetic" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Phonetic" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Phonetic As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Phonetic : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Phonetic" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erstellen von Tokens für phonetischen entspricht.
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-phonetic/org/apache/lucene/analysis/phonetic/package-tree.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PorterStem">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName PorterStem;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName PorterStem" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.PorterStem" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly PorterStem As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable PorterStem : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.PorterStem" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Verwendet die wortstammerkennung Porter-Algorithmus um den Tokenstream zu transformieren.
            <see href="http://tartarus.org/~martin/PorterStemmer/" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reverse">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Reverse;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Reverse" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Reverse" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Reverse As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Reverse : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Reverse" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Kehrt die Tokenzeichenfolge.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/reverse/ReverseStringFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScandinavianFoldingNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName ScandinavianFoldingNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName ScandinavianFoldingNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.ScandinavianFoldingNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly ScandinavianFoldingNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable ScandinavianFoldingNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.ScandinavianFoldingNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Faltet Skandinavische Zeichen åÅäæÄÆ -&gt;ein "und" öÖøØ -&gt;o. Er auch vor Verwendung von doppelten Vokale beibehält aa, Ae, Ao, Oe und Oo, nur die erste Aktivität zu verlassen.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/ScandinavianFoldingFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScandinavianNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName ScandinavianNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName ScandinavianNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.ScandinavianNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly ScandinavianNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable ScandinavianNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.ScandinavianNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Normalisiert die austauschbar Skandinavische Zeichen.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/ScandinavianNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Shingle">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Shingle;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Shingle" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Shingle" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Shingle As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Shingle : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Shingle" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Kombinationen von Token erstellt als ein einzelnes Token.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/shingle/ShingleFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snowball">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Snowball;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Snowball" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Snowball" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Snowball As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Snowball : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Snowball" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ein Filter, der Wörter, wobei eine wortstammerkennung Snowball generierte resultiert.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/snowball/SnowballFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SoraniNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName SoraniNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName SoraniNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.SoraniNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly SoraniNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable SoraniNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.SoraniNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Normalisiert die Unicode-Darstellung des Texts Sorani an.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ckb/SoraniNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stemmer">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Stemmer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Stemmer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Stemmer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Stemmer As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Stemmer : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Stemmer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Bestimmte wortstammerkennung Sprachfilter.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Custom-analyzers-in-Azure-Search#TokenFilters" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stopwords">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Stopwords;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Stopwords" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Stopwords" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Stopwords As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Stopwords : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Stopwords" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Entfernt Stoppwörter einen token Stream heraus.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/StopFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Trim">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Trim;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Trim" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Trim" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Trim As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Trim : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Trim" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Entfernt führende und nachfolgende Leerzeichen aus dem Token.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/TrimFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Truncate">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Truncate;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Truncate" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Truncate" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Truncate As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Truncate : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Truncate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Schneidet die Begriffe zu einer bestimmten Länge ab.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/TruncateTokenFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unique">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Unique;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Unique" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Unique" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Unique As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Unique : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Unique" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Filtert-Token mit den gleichen Text wie der vorherige Token.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/RemoveDuplicatesTokenFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uppercase">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Uppercase;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Uppercase" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Uppercase" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Uppercase As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Uppercase : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Uppercase" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Normalisiert die token-Text in Großbuchstaben.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/UpperCaseFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WordDelimiter">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName WordDelimiter;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName WordDelimiter" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.WordDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly WordDelimiter As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable WordDelimiter : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.WordDelimiter" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Subwords Wörter teilt, und führt optionale Transformationen auf Subword Gruppen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>