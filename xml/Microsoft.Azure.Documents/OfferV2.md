<Type Name="OfferV2" FullName="Microsoft.Azure.Documents.OfferV2">
  <TypeSignature Language="C#" Value="public sealed class OfferV2 : Microsoft.Azure.Documents.Offer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OfferV2 extends Microsoft.Azure.Documents.Offer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.OfferV2" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OfferV2&#xA;Inherits Offer" />
  <TypeSignature Language="F#" Value="type OfferV2 = class&#xA;    inherit Offer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Offer</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6647c-101">Stellt den Standard Preise Angebot für eine Ressource in der Azure-Cosmos-DB-Dienst dar.</span><span class="sxs-lookup"><span data-stu-id="6647c-101">Represents the Standard pricing offer for a resource in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="6647c-102">Angebote sind derzeit nur auf die auflistungsressource gebunden.</span><span class="sxs-lookup"><span data-stu-id="6647c-102">Currently, offers are only bound to the collection resource.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OfferV2 (int offerThroughput);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 offerThroughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.OfferV2.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (offerThroughput As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.OfferV2 : int -&gt; Microsoft.Azure.Documents.OfferV2" Usage="new Microsoft.Azure.Documents.OfferV2 offerThroughput" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="offerThroughput" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="offerThroughput">To be added.</param>
        <summary>
            <span data-ttu-id="6647c-103">Initialisiert ein Angebot Ressource mit der Standard-Tarif für den Azure-Cosmos-DB-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="6647c-103">Initializes a Resource offer with the Standard pricing tier for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OfferV2 (Microsoft.Azure.Documents.Offer offer, int offerThroughput);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Offer offer, int32 offerThroughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.OfferV2.#ctor(Microsoft.Azure.Documents.Offer,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.OfferV2 : Microsoft.Azure.Documents.Offer * int -&gt; Microsoft.Azure.Documents.OfferV2" Usage="new Microsoft.Azure.Documents.OfferV2 (offer, offerThroughput)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="offer" Type="Microsoft.Azure.Documents.Offer" />
        <Parameter Name="offerThroughput" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="offer">To be added.</param>
        <param name="offerThroughput">To be added.</param>
        <summary>
            <span data-ttu-id="6647c-104">Initialisiert ein Angebot für die Ressource mit der Standard-Preisstufe aus einem Verweis angebotsobjekt für den Azure-Cosmos-DB-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="6647c-104">Initializes a Resource offer with the Standard pricing tier, from a reference Offer object for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OfferV2 (int offerThroughput, Nullable&lt;bool&gt; offerEnableRUPerMinuteThroughput);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 offerThroughput, valuetype System.Nullable`1&lt;bool&gt; offerEnableRUPerMinuteThroughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.OfferV2.#ctor(System.Int32,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (offerThroughput As Integer, offerEnableRUPerMinuteThroughput As Nullable(Of Boolean))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.OfferV2 : int * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Documents.OfferV2" Usage="new Microsoft.Azure.Documents.OfferV2 (offerThroughput, offerEnableRUPerMinuteThroughput)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="offerThroughput" Type="System.Int32" />
        <Parameter Name="offerEnableRUPerMinuteThroughput" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="offerThroughput">To be added.</param>
        <param name="offerEnableRUPerMinuteThroughput">To be added.</param>
        <summary>
            <span data-ttu-id="6647c-105">Initialisiert ein Angebot Ressource mit der Standard-Tarif für den Azure-Cosmos-DB-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="6647c-105">Initializes a Resource offer with the Standard pricing tier for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OfferV2 (Microsoft.Azure.Documents.Offer offer, int offerThroughput, Nullable&lt;bool&gt; offerEnableRUPerMinuteThroughput);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Offer offer, int32 offerThroughput, valuetype System.Nullable`1&lt;bool&gt; offerEnableRUPerMinuteThroughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.OfferV2.#ctor(Microsoft.Azure.Documents.Offer,System.Int32,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.OfferV2 : Microsoft.Azure.Documents.Offer * int * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Documents.OfferV2" Usage="new Microsoft.Azure.Documents.OfferV2 (offer, offerThroughput, offerEnableRUPerMinuteThroughput)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="offer" Type="Microsoft.Azure.Documents.Offer" />
        <Parameter Name="offerThroughput" Type="System.Int32" />
        <Parameter Name="offerEnableRUPerMinuteThroughput" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="offer">To be added.</param>
        <param name="offerThroughput">To be added.</param>
        <param name="offerEnableRUPerMinuteThroughput">To be added.</param>
        <summary>
            <span data-ttu-id="6647c-106">Initialisiert ein Angebot für die Ressource mit der Standard-Preisstufe aus einem Verweis angebotsobjekt für den Azure-Cosmos-DB-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="6647c-106">Initializes a Resource offer with the Standard pricing tier, from a reference Offer object for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.OfferContentV2 Content { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.OfferContentV2 Content" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.OfferV2.Content" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Content As OfferContentV2" />
      <MemberSignature Language="F#" Value="member this.Content : Microsoft.Azure.Documents.OfferContentV2" Usage="Microsoft.Azure.Documents.OfferV2.Content" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, PropertyName="content")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.OfferContentV2</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6647c-107">Ruft ab oder legt die OfferContent für das Angebot an Ressourcen im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="6647c-107">Gets or sets the OfferContent for the resource offer in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>