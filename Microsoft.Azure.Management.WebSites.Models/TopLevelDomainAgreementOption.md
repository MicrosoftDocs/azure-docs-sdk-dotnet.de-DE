<Type Name="TopLevelDomainAgreementOption" FullName="Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption">
  <TypeSignature Language="C#" Value="public class TopLevelDomainAgreementOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopLevelDomainAgreementOption extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption" />
  <TypeSignature Language="VB.NET" Value="Public Class TopLevelDomainAgreementOption" />
  <TypeSignature Language="F#" Value="type TopLevelDomainAgreementOption = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Optionen für das Abrufen der Liste der Domäne der obersten Ebene rechtsgültige Verträge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopLevelDomainAgreementOption ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TopLevelDomainAgreementOption-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopLevelDomainAgreementOption (Nullable&lt;bool&gt; includePrivacy = null, Nullable&lt;bool&gt; forTransfer = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; includePrivacy, valuetype System.Nullable`1&lt;bool&gt; forTransfer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.#ctor(System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional includePrivacy As Nullable(Of Boolean) = null, Optional forTransfer As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption : Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption" Usage="new Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption (includePrivacy, forTransfer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="includePrivacy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="forTransfer" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="includePrivacy">Wenn &lt;Code&gt;"true"&lt;/code&gt;, und klicken Sie dann die Liste der Verträge Vereinbarungen für Domäne Datenschutz, wie gut ist, andernfalls aufnimmt &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="forTransfer">Wenn &lt;Code&gt;"true"&lt;/code&gt;, und klicken Sie dann die Liste der Verträge Vereinbarungen für die Übertragung der Domäne, wie gut ist, andernfalls aufnimmt &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <summary>
            Initialisiert eine neue Instanz der TopLevelDomainAgreementOption-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForTransfer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ForTransfer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ForTransfer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.ForTransfer" />
      <MemberSignature Language="VB.NET" Value="Public Property ForTransfer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ForTransfer : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.ForTransfer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="forTransfer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wenn &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; und klicken Sie dann die Liste der Verträge Vereinbarungen für die Übertragung der Domäne, wie gut ist, andernfalls aufnimmt &amp;Lt; Code&amp;Gt; "false"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludePrivacy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IncludePrivacy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IncludePrivacy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.IncludePrivacy" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludePrivacy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IncludePrivacy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.IncludePrivacy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="includePrivacy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wenn &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; und klicken Sie dann die Liste der Verträge Vereinbarungen für Domäne Datenschutz, wie gut ist, andernfalls aufnimmt &amp;Lt; Code&amp;Gt; "false"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>