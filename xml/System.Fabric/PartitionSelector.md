<Type Name="PartitionSelector" FullName="System.Fabric.PartitionSelector">
  <TypeSignature Language="C#" Value="public class PartitionSelector" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit PartitionSelector extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PartitionSelector" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionSelector" />
  <TypeSignature Language="F#" Value="type PartitionSelector = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92dd8-101">Dies ist eine Hilfsklasse für Partitionen auswählen.</span><span class="sxs-lookup"><span data-stu-id="92dd8-101">This is a helper class for selecting partitions.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="92dd8-102">Sie können den Benutzer zur Auswahl von Partitionen an, für die Prüfbarkeit APIs konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="92dd8-102">It allows the user to select partitions to be targeted by the testability APIs.</span></span> <span data-ttu-id="92dd8-103">Die Auswahl kann eine bestimmte Partition eines Diensts auf Grundlage der Id oder Schlüssel oder eine zufällige Partition eines Diensts sein.</span><span class="sxs-lookup"><span data-stu-id="92dd8-103">The selection can be a particular partition of a service based on the Id or Key or a random partition of a service.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="partitionSelector.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="92dd8-104">PartitionSelector, t.o verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="92dd8-104">PartitionSelector to compare t.o</span></span></param>
        <summary>
            <span data-ttu-id="92dd8-105">Vergleicht, ob zwei PartitionSelectors identisch sind.</span><span class="sxs-lookup"><span data-stu-id="92dd8-105">Compares whether two PartitionSelectors are the same.</span></span>
            </summary>
        <returns><span data-ttu-id="92dd8-106">"true", wenn "false" ist dies nicht.</span><span class="sxs-lookup"><span data-stu-id="92dd8-106">true if same false if not.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="partitionSelector.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92dd8-107">Ruft die Basis GetHashCode()</span><span class="sxs-lookup"><span data-stu-id="92dd8-107">Calls the base GetHashCode()</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionIdOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.PartitionSelector PartitionIdOf (Uri serviceName, Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.PartitionSelector PartitionIdOf(class System.Uri serviceName, valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.PartitionIdOf(System.Uri,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PartitionIdOf (serviceName As Uri, partitionId As Guid) As PartitionSelector" />
      <MemberSignature Language="F#" Value="static member PartitionIdOf : Uri * Guid -&gt; System.Fabric.PartitionSelector" Usage="System.Fabric.PartitionSelector.PartitionIdOf (serviceName, partitionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="serviceName"><span data-ttu-id="92dd8-108">Der Name des Diensts, deren Partition muss ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="92dd8-108">Name of the service whose partition needs to be selected.</span></span></param>
        <param name="partitionId"><span data-ttu-id="92dd8-109">Die PartitionId für die Partition.</span><span class="sxs-lookup"><span data-stu-id="92dd8-109">The PartitionId for the partition.</span></span></param>
        <summary>
            <span data-ttu-id="92dd8-110">Wählt eine Partition für den Dienst, der die PartitionId angegeben.</span><span class="sxs-lookup"><span data-stu-id="92dd8-110">Selects a partition for the service given the PartitionId.</span></span>
            </summary>
        <returns><span data-ttu-id="92dd8-111">Erstellt von PartitionSelector.</span><span class="sxs-lookup"><span data-stu-id="92dd8-111">Constructed PartitionSelector.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.PartitionSelector PartitionKeyOf (Uri serviceName, long partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.PartitionSelector PartitionKeyOf(class System.Uri serviceName, int64 partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.PartitionKeyOf(System.Uri,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PartitionKeyOf (serviceName As Uri, partitionKey As Long) As PartitionSelector" />
      <MemberSignature Language="F#" Value="static member PartitionKeyOf : Uri * int64 -&gt; System.Fabric.PartitionSelector" Usage="System.Fabric.PartitionSelector.PartitionKeyOf (serviceName, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="serviceName"><span data-ttu-id="92dd8-112">Der Name des Diensts, deren Partition muss ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="92dd8-112">Name of the service whose partition needs to be selected.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="92dd8-113">Der Partitionsschlüssel der angehört. die Partition ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="92dd8-113">The partition key which belongs to the partition to be selected.</span></span></param>
        <summary>
            <span data-ttu-id="92dd8-114">Wählt eine Partition für den Dienst, den der angegebenen Partitionsschlüssel angehört.</span><span class="sxs-lookup"><span data-stu-id="92dd8-114">Selects a partition for the service to which the specified partition key belongs.</span></span>
            </summary>
        <returns><span data-ttu-id="92dd8-115">Erstellt von PartitionSelector.</span><span class="sxs-lookup"><span data-stu-id="92dd8-115">Constructed PartitionSelector.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.PartitionSelector PartitionKeyOf (Uri serviceName, string partitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.PartitionSelector PartitionKeyOf(class System.Uri serviceName, string partitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.PartitionKeyOf(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PartitionKeyOf (serviceName As Uri, partitionName As String) As PartitionSelector" />
      <MemberSignature Language="F#" Value="static member PartitionKeyOf : Uri * string -&gt; System.Fabric.PartitionSelector" Usage="System.Fabric.PartitionSelector.PartitionKeyOf (serviceName, partitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName"><span data-ttu-id="92dd8-116">Der Name des Diensts, deren Partition muss ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="92dd8-116">Name of the service whose partition needs to be selected.</span></span></param>
        <param name="partitionName"><span data-ttu-id="92dd8-117">Der Name der Partition, die muss ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="92dd8-117">Name of the partition that needs to be selected.</span></span></param>
        <summary>
            <span data-ttu-id="92dd8-118">Wählt eine Partition für den Dienst mit den angegebenen PartitionName an.</span><span class="sxs-lookup"><span data-stu-id="92dd8-118">Selects a partition for the service with the specified PartitionName.</span></span>
            </summary>
        <returns><span data-ttu-id="92dd8-119">Erstellt von PartitionSelector.</span><span class="sxs-lookup"><span data-stu-id="92dd8-119">Constructed PartitionSelector.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RandomOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.PartitionSelector RandomOf (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.PartitionSelector RandomOf(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.RandomOf(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RandomOf (serviceName As Uri) As PartitionSelector" />
      <MemberSignature Language="F#" Value="static member RandomOf : Uri -&gt; System.Fabric.PartitionSelector" Usage="System.Fabric.PartitionSelector.RandomOf serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName"><span data-ttu-id="92dd8-120">Der Name des Diensts, deren Partition muss ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="92dd8-120">Name of the service whose partition needs to be selected.</span></span></param>
        <summary>
            <span data-ttu-id="92dd8-121">Wählt eine zufällige Partition aus, für den angegebenen Dienst.</span><span class="sxs-lookup"><span data-stu-id="92dd8-121">Selects a random partition for given service.</span></span>
            </summary>
        <returns><span data-ttu-id="92dd8-122">Erstellt von PartitionSelector.</span><span class="sxs-lookup"><span data-stu-id="92dd8-122">Constructed PartitionSelector.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SingletonOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.PartitionSelector SingletonOf (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.PartitionSelector SingletonOf(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.SingletonOf(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SingletonOf (serviceName As Uri) As PartitionSelector" />
      <MemberSignature Language="F#" Value="static member SingletonOf : Uri -&gt; System.Fabric.PartitionSelector" Usage="System.Fabric.PartitionSelector.SingletonOf serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName"><span data-ttu-id="92dd8-123">Der Name des Diensts, deren Partition muss ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="92dd8-123">Name of the service whose partition needs to be selected.</span></span></param>
        <summary>
            <span data-ttu-id="92dd8-124">Wählt die Singleton-Partition für einen Dienst an.</span><span class="sxs-lookup"><span data-stu-id="92dd8-124">Selects the singleton partition for a service.</span></span>
            </summary>
        <returns><span data-ttu-id="92dd8-125">Erstellt von PartitionSelector.</span><span class="sxs-lookup"><span data-stu-id="92dd8-125">Constructed PartitionSelector.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionSelector.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92dd8-126">Die Zeichenfolgendarstellung der Partition Selektor.</span><span class="sxs-lookup"><span data-stu-id="92dd8-126">String representation of the partition selector.</span></span>
            </summary>
        <returns><span data-ttu-id="92dd8-127">Eine Zeichenfolgendarstellung der Selektor.</span><span class="sxs-lookup"><span data-stu-id="92dd8-127">A string representation of the selector.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>