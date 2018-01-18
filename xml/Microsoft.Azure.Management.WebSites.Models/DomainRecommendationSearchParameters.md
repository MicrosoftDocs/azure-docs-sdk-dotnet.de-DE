<Type Name="DomainRecommendationSearchParameters" FullName="Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters">
  <TypeSignature Language="C#" Value="public class DomainRecommendationSearchParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DomainRecommendationSearchParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class DomainRecommendationSearchParameters" />
  <TypeSignature Language="F#" Value="type DomainRecommendationSearchParameters = class" />
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
            <span data-ttu-id="795bf-101">Domäne Empfehlung Suchparameter angegeben.</span><span class="sxs-lookup"><span data-stu-id="795bf-101">Domain recommendation search parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainRecommendationSearchParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="795bf-102">Initialisiert eine neue Instanz der DomainRecommendationSearchParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="795bf-102">Initializes a new instance of the DomainRecommendationSearchParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainRecommendationSearchParameters (string keywords = null, Nullable&lt;int&gt; maxDomainRecommendations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keywords, valuetype System.Nullable`1&lt;int32&gt; maxDomainRecommendations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional keywords As String = null, Optional maxDomainRecommendations As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters" Usage="new Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters (keywords, maxDomainRecommendations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keywords" Type="System.String" />
        <Parameter Name="maxDomainRecommendations" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="keywords"><span data-ttu-id="795bf-103">Die Schlüsselwörter zum Generieren von Empfehlungen Domäne verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="795bf-103">Keywords to be used for generating domain recommendations.</span></span></param>
        <param name="maxDomainRecommendations"><span data-ttu-id="795bf-104">Maximale Anzahl von Empfehlungen.</span><span class="sxs-lookup"><span data-stu-id="795bf-104">Maximum number of recommendations.</span></span></param>
        <summary>
            <span data-ttu-id="795bf-105">Initialisiert eine neue Instanz der DomainRecommendationSearchParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="795bf-105">Initializes a new instance of the DomainRecommendationSearchParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keywords">
      <MemberSignature Language="C#" Value="public string Keywords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Keywords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters.Keywords" />
      <MemberSignature Language="VB.NET" Value="Public Property Keywords As String" />
      <MemberSignature Language="F#" Value="member this.Keywords : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters.Keywords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keywords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="795bf-106">Ruft ab, oder legt ihn fest Schlüsselwörter zum Generieren von Empfehlungen Domäne verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="795bf-106">Gets or sets keywords to be used for generating domain recommendations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDomainRecommendations">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDomainRecommendations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDomainRecommendations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters.MaxDomainRecommendations" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDomainRecommendations As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDomainRecommendations : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters.MaxDomainRecommendations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxDomainRecommendations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="795bf-107">Ruft ab oder legt die maximale Anzahl von Empfehlungen.</span><span class="sxs-lookup"><span data-stu-id="795bf-107">Gets or sets maximum number of recommendations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>