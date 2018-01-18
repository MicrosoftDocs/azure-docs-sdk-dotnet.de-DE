<Type Name="ReplicaSelector" FullName="System.Fabric.ReplicaSelector">
  <TypeSignature Language="C#" Value="public class ReplicaSelector" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ReplicaSelector extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReplicaSelector" />
  <TypeSignature Language="VB.NET" Value="Public Class ReplicaSelector" />
  <TypeSignature Language="F#" Value="type ReplicaSelector = class" />
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
            <span data-ttu-id="4d1db-101">Dies ist eine Hilfsklasse für die Auswahl der Replikate.</span><span class="sxs-lookup"><span data-stu-id="4d1db-101">This is a helper class for selecting replicas.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="4d1db-102">Sie können den Benutzer zur Auswahl der Replikate an, für die Prüfbarkeit APIs konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="4d1db-102">It allows the user to select replicas to be targeted by the testability APIs.</span></span> <span data-ttu-id="4d1db-103">Die Auswahl kann es sich um ein bestimmtes Replikat einer Partition basierend auf den ReplicaId oder Rolle oder einen zufälligen Replikat der Partition sein.</span><span class="sxs-lookup"><span data-stu-id="4d1db-103">The selection can be a particular replica of a partition based on the ReplicaId or Role or a random replica of the partition.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicaSelector.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="replicaSelector.Equals obj" />
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
        <param name="obj"><span data-ttu-id="4d1db-104">ReplicaSelector verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4d1db-104">ReplicaSelector to compare to.</span></span></param>
        <summary>
            <span data-ttu-id="4d1db-105">Vergleicht, ob zwei ReplicaSelectors identisch sind.</span><span class="sxs-lookup"><span data-stu-id="4d1db-105">Compares whether two ReplicaSelectors are the same.</span></span>
            </summary>
        <returns><span data-ttu-id="4d1db-106">"true", wenn "false" ist dies nicht.</span><span class="sxs-lookup"><span data-stu-id="4d1db-106">true if same false if not.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicaSelector.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="replicaSelector.GetHashCode " />
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
            <span data-ttu-id="4d1db-107">Ruft die Basis GetHashCode()</span><span class="sxs-lookup"><span data-stu-id="4d1db-107">Calls the base GetHashCode()</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionSelector">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionSelector PartitionSelector { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.PartitionSelector PartitionSelector" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicaSelector.PartitionSelector" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionSelector As PartitionSelector" />
      <MemberSignature Language="F#" Value="member this.PartitionSelector : System.Fabric.PartitionSelector" Usage="System.Fabric.ReplicaSelector.PartitionSelector" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d1db-108">Die PartitionSelector angeben der Partitions, für die das Replikat von der ReplicaSelector ausgewählt ist.</span><span class="sxs-lookup"><span data-stu-id="4d1db-108">The PartitionSelector specifying the partition for which the replica is being selected by the ReplicaSelector.</span></span>
            </summary>
        <value><span data-ttu-id="4d1db-109">Das PartitionSelector-Objekt.</span><span class="sxs-lookup"><span data-stu-id="4d1db-109">The PartitionSelector object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.ReplicaSelector PrimaryOf (System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.ReplicaSelector PrimaryOf(class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicaSelector.PrimaryOf(System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="static member PrimaryOf : System.Fabric.PartitionSelector -&gt; System.Fabric.ReplicaSelector" Usage="System.Fabric.ReplicaSelector.PrimaryOf partitionSelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="4d1db-110">PartitionSelector, womit die Partition, deren Replikat muss ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="4d1db-110">PartitionSelector which indicates the partition whose replica needs to be selected.</span></span></param>
        <summary>
            <span data-ttu-id="4d1db-111">Wählt das primäre Replikat für die angegebene Partition, die durch die PartitionSelector angegeben.</span><span class="sxs-lookup"><span data-stu-id="4d1db-111">Selects the primary replica for the given partition specified by the PartitionSelector.</span></span>
            </summary>
        <returns><span data-ttu-id="4d1db-112">Erstellt von ReplicaSelector.</span><span class="sxs-lookup"><span data-stu-id="4d1db-112">Constructed ReplicaSelector.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RandomOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.ReplicaSelector RandomOf (System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.ReplicaSelector RandomOf(class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicaSelector.RandomOf(System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="static member RandomOf : System.Fabric.PartitionSelector -&gt; System.Fabric.ReplicaSelector" Usage="System.Fabric.ReplicaSelector.RandomOf partitionSelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="4d1db-113">PartitionSelector, womit die Partition, deren Replikat muss ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="4d1db-113">PartitionSelector which indicates the partition whose replica needs to be selected.</span></span></param>
        <summary>
            <span data-ttu-id="4d1db-114">Wählt einen zufälligen Replikat für die angegebene Partition, die durch die PartitionSelector angegeben.</span><span class="sxs-lookup"><span data-stu-id="4d1db-114">Selects a random replica for the given partition specified by the PartitionSelector.</span></span>
            </summary>
        <returns><span data-ttu-id="4d1db-115">Erstellt von ReplicaSelector.</span><span class="sxs-lookup"><span data-stu-id="4d1db-115">Constructed ReplicaSelector.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RandomSecondaryOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.ReplicaSelector RandomSecondaryOf (System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.ReplicaSelector RandomSecondaryOf(class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicaSelector.RandomSecondaryOf(System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="static member RandomSecondaryOf : System.Fabric.PartitionSelector -&gt; System.Fabric.ReplicaSelector" Usage="System.Fabric.ReplicaSelector.RandomSecondaryOf partitionSelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="4d1db-116">PartitionSelector, womit die Partition, deren Replikat muss ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="4d1db-116">PartitionSelector which indicates the partition whose replica needs to be selected.</span></span></param>
        <summary>
            <span data-ttu-id="4d1db-117">Wählt ein zufälliges sekundäres Replikat für die angegebene Partition, die durch die PartitionSelector angegeben.</span><span class="sxs-lookup"><span data-stu-id="4d1db-117">Selects a random secondary replica for the given partition specified by the PartitionSelector.</span></span>
            </summary>
        <returns><span data-ttu-id="4d1db-118">Erstellt von ReplicaSelector.</span><span class="sxs-lookup"><span data-stu-id="4d1db-118">Constructed ReplicaSelector.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaIdOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.ReplicaSelector ReplicaIdOf (System.Fabric.PartitionSelector partitionSelector, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.ReplicaSelector ReplicaIdOf(class System.Fabric.PartitionSelector partitionSelector, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicaSelector.ReplicaIdOf(System.Fabric.PartitionSelector,System.Int64)" />
      <MemberSignature Language="F#" Value="static member ReplicaIdOf : System.Fabric.PartitionSelector * int64 -&gt; System.Fabric.ReplicaSelector" Usage="System.Fabric.ReplicaSelector.ReplicaIdOf (partitionSelector, replicaOrInstanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="4d1db-119">PartitionSelector, womit die Partition, deren Replikat muss ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="4d1db-119">PartitionSelector which indicates the partition whose replica needs to be selected.</span></span></param>
        <param name="replicaOrInstanceId"><span data-ttu-id="4d1db-120">ReplicaOrInstanceId für das Replikat oder eine Instanz ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="4d1db-120">ReplicaOrInstanceId for the replica or instance to be selected.</span></span></param>
        <summary>
            <span data-ttu-id="4d1db-121">Wählt ein Replikat basierend auf den ReplicaId für die angegebene Partition, die durch die PartitionSelector angegeben.</span><span class="sxs-lookup"><span data-stu-id="4d1db-121">Selects a replica based on the ReplicaId for the given partition specified by the PartitionSelector.</span></span>
            </summary>
        <returns><span data-ttu-id="4d1db-122">Ein <see cref="T:System.Fabric.ReplicaSelector" /> auf Grundlage der Eingabe übergeben.</span><span class="sxs-lookup"><span data-stu-id="4d1db-122">A <see cref="T:System.Fabric.ReplicaSelector" /> based on the input passed in.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicaSelector.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="replicaSelector.ToString " />
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
            <span data-ttu-id="4d1db-123">Die Zeichenfolgendarstellung der Replikat-Selektor.</span><span class="sxs-lookup"><span data-stu-id="4d1db-123">String representation of the replica selector.</span></span>
            </summary>
        <returns><span data-ttu-id="4d1db-124">Eine Zeichenfolgendarstellung der Selektor.</span><span class="sxs-lookup"><span data-stu-id="4d1db-124">A string representation of the selector.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>