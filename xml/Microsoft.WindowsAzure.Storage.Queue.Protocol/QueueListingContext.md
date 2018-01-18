<Type Name="QueueListingContext" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingContext">
  <TypeSignature Language="C#" Value="public sealed class QueueListingContext : Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit QueueListingContext extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class QueueListingContext&#xA;Inherits ListingContext" />
  <TypeSignature Language="F#" Value="type QueueListingContext = class&#xA;    inherit ListingContext" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="80e48-101">Stellt einen Satz von Parametern für eine Warteschlange Auflistungsvorgang bereit.</span><span class="sxs-lookup"><span data-stu-id="80e48-101">Provides a set of parameters for a queue listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueListingContext (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails include);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails include) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingContext.#ctor(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (prefix As String, maxResults As Nullable(Of Integer), include As QueueListingDetails)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingContext : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingContext" Usage="new Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingContext (prefix, maxResults, include)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="include" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="80e48-102">Das Präfix des Warteschlangennamens.</span><span class="sxs-lookup"><span data-stu-id="80e48-102">The queue prefix.</span></span></param>
        <param name="maxResults"><span data-ttu-id="80e48-103">Die maximale Anzahl der zurückzugebenden Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="80e48-103">The maximum number of results to return.</span></span></param>
        <param name="include"><span data-ttu-id="80e48-104">Der Include-Parameter.</span><span class="sxs-lookup"><span data-stu-id="80e48-104">The include parameter.</span></span></param>
        <summary>
            <span data-ttu-id="80e48-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingContext" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="80e48-105">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Include">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails Include { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails Include" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingContext.Include" />
      <MemberSignature Language="VB.NET" Value="Public Property Include As QueueListingDetails" />
      <MemberSignature Language="F#" Value="member this.Include : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingContext.Include" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80e48-106">Ruft ab oder legt die Details für die Auflistungsvorgang, womit die Typen von Daten in der Antwort eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="80e48-106">Gets or sets the details for the listing operation, which indicates the types of data to include in the response.</span></span>
            </summary>
        <value><span data-ttu-id="80e48-107">Die Details in den Auflistungsvorgang eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="80e48-107">The details to include in the listing operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>