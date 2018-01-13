<Type Name="WinRMListener" FullName="Microsoft.Azure.Management.Compute.Models.WinRMListener">
  <TypeSignature Language="C#" Value="public class WinRMListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WinRMListener extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.WinRMListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WinRMListener" />
  <TypeSignature Language="F#" Value="type WinRMListener = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibt, Protokoll und den Fingerabdruck des Listeners für Windows-Remoteverwaltung
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WinRMListener ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.WinRMListener.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der WinRMListener-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WinRMListener (Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; protocol = null, string certificateUrl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; protocol, string certificateUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.WinRMListener.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.ProtocolTypes},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional protocol As Nullable(Of ProtocolTypes) = null, Optional certificateUrl As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.WinRMListener : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.WinRMListener" Usage="new Microsoft.Azure.Management.Compute.Models.WinRMListener (protocol, certificateUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt;" />
        <Parameter Name="certificateUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol">Gibt das Protokoll des Listeners.
            &lt;Brasilien&gt;&lt;Br&gt; folgende Werte sind möglich: &lt;Br&gt;**http** &lt;Br&gt;&lt;Br&gt; ** HTTPS**. Folgende Werte sind möglich: "Http", "Https"</param>
        <param name="certificateUrl">Dies ist die URL eines Zertifikats, das in den Key Vault als ein geheimer Schlüssel hochgeladen wurde. Der Schlüsseltresor einen geheimer Schlüssel hinzufügen, finden Sie unter [Hinzufügen eines Schlüssels oder den geheimen Schlüssel für den schlüsseltresor](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add).
            In diesem Fall ist die Base64-Codierung der folgenden JSON-Objekt, das Ihrem Zertifikat muss in UTF-8 codiert ist: &lt;Br&gt;&lt;Br&gt; {&lt;Br&gt; "Daten": "&lt; Base64-codierten Zertifikats&gt;",&lt;Br&gt; "DataType":"Pfx",&lt;Br&gt; "Password":"&lt;Pfx-Datei-Password&gt;"&lt;Br&gt;}</param>
        <summary>
            Initialisiert eine neue Instanz der WinRMListener-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateUrl">
      <MemberSignature Language="C#" Value="public string CertificateUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.WinRMListener.CertificateUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateUrl As String" />
      <MemberSignature Language="F#" Value="member this.CertificateUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.WinRMListener.CertificateUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, ist dies die URL eines Zertifikats, das in den Key Vault als ein geheimer Schlüssel hochgeladen wurde. Der Schlüsseltresor einen geheimer Schlüssel hinzufügen, finden Sie unter [Hinzufügen eines Schlüssels oder den geheimen Schlüssel für den schlüsseltresor](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add).
            In diesem Fall ist die Base64-Codierung der folgenden JSON-Objekt, das Ihrem Zertifikat muss in UTF-8 codiert ist: &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; {&amp;Lt; Br&amp;Gt; "Daten": "&amp;Lt; Base64-codierten Zertifikats&amp;Gt; ",&amp;Lt; Br&amp;Gt; "DataType": "Pfx",&amp;Lt; Br&amp;Gt; "Password": "&amp;Lt; Pfx-Datei-Password&amp;Gt;" &amp;Lt; Br&amp;Gt;}
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.WinRMListener.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As Nullable(Of ProtocolTypes)" />
      <MemberSignature Language="F#" Value="member this.Protocol : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.WinRMListener.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt das Protokoll des Listeners an.
            &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Mögliche Werte sind: &amp;Lt; Br&amp;Gt;** HTTP** &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Https**. Folgende Werte sind möglich: "Http", "Https"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>