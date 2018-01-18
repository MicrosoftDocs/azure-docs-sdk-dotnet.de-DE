<Type Name="StatefulServiceLoadMetricDescription" FullName="System.Fabric.Description.StatefulServiceLoadMetricDescription">
  <TypeSignature Language="C#" Value="public sealed class StatefulServiceLoadMetricDescription : System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServiceLoadMetricDescription extends System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServiceLoadMetricDescription&#xA;Inherits ServiceLoadMetricDescription" />
  <TypeSignature Language="F#" Value="type StatefulServiceLoadMetricDescription = class&#xA;    inherit ServiceLoadMetricDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceLoadMetricDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="2d057-101">Gibt eine Metrik für ein zustandsbehafteter Dienst an.</span><span class="sxs-lookup"><span data-stu-id="2d057-101">Specifies a metric for a stateful service.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceLoadMetricDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatefulServiceLoadMetricDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="2d057-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2d057-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryDefaultLoad">
      <MemberSignature Language="C#" Value="public int PrimaryDefaultLoad { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrimaryDefaultLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceLoadMetricDescription.PrimaryDefaultLoad" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryDefaultLoad As Integer" />
      <MemberSignature Language="F#" Value="member this.PrimaryDefaultLoad : int with get, set" Usage="System.Fabric.Description.StatefulServiceLoadMetricDescription.PrimaryDefaultLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2d057-103">Ruft ab oder Festlegen der Standarddauer der Auslastung, die diesen Dienst für die Metrik generiert wird, wenn es sich um ein primäres Replikat ist.</span><span class="sxs-lookup"><span data-stu-id="2d057-103">Gets or sets the default amount of load that this service creates for this metric when it is a Primary replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2d057-104">Die Standarddauer an der Auslastung, die diesen Dienst für die Metrik generiert wird, wenn es sich um ein primäres Replikat ist.</span><span class="sxs-lookup"><span data-stu-id="2d057-104">The default amount of load that this service creates for this metric when it is a Primary replica.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="2d057-105">Angeben von Standardwerten der Last für benutzerdefinierte Metriken kann Ressourcen-Manager von Service Fabric Cluster Services effizient zu platzieren, wenn sie zuerst erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="2d057-105">Specifying default load values for custom metrics enables the Service Fabric Cluster Resource Manager to efficiently place services when they are first created.</span></span>        
             <span data-ttu-id="2d057-106">Wenn Standard Laden nicht angegeben, dass Service Fabric-Cluster-Ressourcen-Manager keine Last für dieses Replikat angenommen, bis das primäre Replikat dieses Diensts ihrer Auslastung meldet.</span><span class="sxs-lookup"><span data-stu-id="2d057-106">If default load is not specified Service Fabric Cluster Resource Manager will assume zero load for this replica until the primary replica of this service reports its load.</span></span>         
            <span data-ttu-id="2d057-107"><see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="2d057-107"><see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />.</span></span>       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryDefaultLoad">
      <MemberSignature Language="C#" Value="public int SecondaryDefaultLoad { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SecondaryDefaultLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceLoadMetricDescription.SecondaryDefaultLoad" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryDefaultLoad As Integer" />
      <MemberSignature Language="F#" Value="member this.SecondaryDefaultLoad : int with get, set" Usage="System.Fabric.Description.StatefulServiceLoadMetricDescription.SecondaryDefaultLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2d057-108">Ruft ab oder Festlegen der Standarddauer der Auslastung, die diesen Dienst für die Metrik generiert wird, wenn es sich um ein sekundäres Replikat ist.</span><span class="sxs-lookup"><span data-stu-id="2d057-108">Gets or sets the default amount of load that this service creates for this metric when it is a Secondary replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2d057-109">Die Standarddauer an der Auslastung, die diesen Dienst für die Metrik generiert wird, wenn es sich um ein sekundäres Replikat ist.</span><span class="sxs-lookup"><span data-stu-id="2d057-109">The default amount of load that this service creates for this metric when it is a Secondary replica.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="2d057-110">Angeben von Standardwerten der Last für benutzerdefinierte Metriken kann Ressourcen-Manager von Service Fabric Cluster Services effizient zu platzieren, wenn sie zuerst erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="2d057-110">Specifying default load values for custom metrics enables the Service Fabric Cluster Resource Manager to efficiently place services when they are first created.</span></span>        
             <span data-ttu-id="2d057-111">Wenn Standard Laden nicht angegeben, dass Service Fabric-Cluster-Ressourcen-Manager keine Last für dieses Replikat angenommen, bis das sekundäre Replikat von diesem Dienst ihrer Auslastung meldet.</span><span class="sxs-lookup"><span data-stu-id="2d057-111">If default load is not specified Service Fabric Cluster Resource Manager will assume zero load for this replica until the secondary replica of this service reports its load.</span></span>         
            <span data-ttu-id="2d057-112"><see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="2d057-112"><see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />.</span></span>        
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatefulServiceLoadMetricDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="statefulServiceLoadMetricDescription.ToString " />
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
            <span data-ttu-id="2d057-113">Details der Schöndruck <see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />.</span><span class="sxs-lookup"><span data-stu-id="2d057-113">Pretty print out details of <see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />.</span></span>
            </summary>
        <returns><span data-ttu-id="2d057-114">Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />.</span><span class="sxs-lookup"><span data-stu-id="2d057-114">A string representation of the <see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <example>
            <span data-ttu-id="2d057-115">CPU, hoch, 90, 10</span><span class="sxs-lookup"><span data-stu-id="2d057-115">CPU,High,90,10</span></span>
            </example>
      </Docs>
    </Member>
  </Members>
</Type>