<Type Name="LegacyApplianceConfigParser" FullName="Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceConfigParser">
  <TypeSignature Language="C#" Value="public class LegacyApplianceConfigParser" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LegacyApplianceConfigParser extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceConfigParser" />
  <TypeSignature Language="VB.NET" Value="Public Class LegacyApplianceConfigParser" />
  <TypeSignature Language="F#" Value="type LegacyApplianceConfigParser = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b842d-101">Legacy-Appliance Config parser</span><span class="sxs-lookup"><span data-stu-id="b842d-101">Legacy appliance config parser</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LegacyApplianceConfigParser (Microsoft.WindowsAzure.Management.StorSimple.IServiceSecretEncryptor encryptor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Management.StorSimple.IServiceSecretEncryptor encryptor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceConfigParser.#ctor(Microsoft.WindowsAzure.Management.StorSimple.IServiceSecretEncryptor)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (encryptor As IServiceSecretEncryptor)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceConfigParser : Microsoft.WindowsAzure.Management.StorSimple.IServiceSecretEncryptor -&gt; Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceConfigParser" Usage="new Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceConfigParser encryptor" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="encryptor" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceSecretEncryptor" />
      </Parameters>
      <Docs>
        <param name="encryptor"><span data-ttu-id="b842d-102">einfache Dienstclient STOR</span><span class="sxs-lookup"><span data-stu-id="b842d-102">stor simple service client</span></span></param>
        <summary>
            <span data-ttu-id="b842d-103">LegacyApplianceConfig-Parser-Konstruktor</span><span class="sxs-lookup"><span data-stu-id="b842d-103">LegacyApplianceConfig Parser constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLegacyApplianceConfig">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceDetails ParseLegacyApplianceConfig (string filePath, string decryptionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceDetails ParseLegacyApplianceConfig(string filePath, string decryptionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceConfigParser.ParseLegacyApplianceConfig(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ParseLegacyApplianceConfig (filePath As String, decryptionKey As String) As LegacyApplianceDetails" />
      <MemberSignature Language="F#" Value="member this.ParseLegacyApplianceConfig : string * string -&gt; Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceDetails" Usage="legacyApplianceConfigParser.ParseLegacyApplianceConfig (filePath, decryptionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceDetails</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="decryptionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filePath"><span data-ttu-id="b842d-104">Pfad der Config-Datei</span><span class="sxs-lookup"><span data-stu-id="b842d-104">config file path</span></span></param>
        <param name="decryptionKey"><span data-ttu-id="b842d-105">Schlüssel zum Entschlüsseln der Datei "App.config"</span><span class="sxs-lookup"><span data-stu-id="b842d-105">key to decrypt the config file</span></span></param>
        <summary>
            <span data-ttu-id="b842d-106">Analysieren von legacy-Appliance-Konfiguration</span><span class="sxs-lookup"><span data-stu-id="b842d-106">Parse legacy appliance config</span></span>
            </summary>
        <returns><span data-ttu-id="b842d-107">Legacy-Appliance-Konfiguration</span><span class="sxs-lookup"><span data-stu-id="b842d-107">legacy appliance config</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParserMessages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Customization.Models.LegacyParserMessage&gt; ParserMessages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.List`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Customization.Models.LegacyParserMessage&gt; ParserMessages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceConfigParser.ParserMessages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ParserMessages As List(Of LegacyParserMessage)" />
      <MemberSignature Language="F#" Value="member this.ParserMessages : System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Customization.Models.LegacyParserMessage&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.LegacyApplianceConfigParser.ParserMessages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Customization.Models.LegacyParserMessage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b842d-108">Ruft die Parser-Meldung ab</span><span class="sxs-lookup"><span data-stu-id="b842d-108">Gets the parser message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>