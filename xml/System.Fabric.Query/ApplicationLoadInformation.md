<Type Name="ApplicationLoadInformation" FullName="System.Fabric.Query.ApplicationLoadInformation">
  <TypeSignature Language="C#" Value="public class ApplicationLoadInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationLoadInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationLoadInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationLoadInformation" />
  <TypeSignature Language="F#" Value="type ApplicationLoadInformation = class" />
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
      <para> <span data-ttu-id="4002f-101">Beschreibt das Laden der eine Anwendungsinstanz, die mit abgerufen wird<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String)" /></span><span class="sxs-lookup"><span data-stu-id="4002f-101">Describes the load of an application instance that is retrieved using <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String)" /></span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationLoadInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="4002f-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4002f-102">Initializes a new instance of the <see cref="T:System.Fabric.Query.ApplicationLoadInformation" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLoadMetricInformation">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.ApplicationLoadMetricInformation&gt; ApplicationLoadMetricInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ApplicationLoadMetricInformation&gt; ApplicationLoadMetricInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.ApplicationLoadMetricInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationLoadMetricInformation As IList(Of ApplicationLoadMetricInformation)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLoadMetricInformation : System.Collections.Generic.IList&lt;System.Fabric.Query.ApplicationLoadMetricInformation&gt;" Usage="System.Fabric.Query.ApplicationLoadInformation.ApplicationLoadMetricInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.ApplicationLoadMetricInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4002f-103">Ruft die Liste der Ladevorgängen pro Metrik für diese Anwendungsinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="4002f-103">Gets the list of loads per metric for this application instance.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4002f-104">Die Liste der Ladevorgängen pro Metrik für diese Anwendungsinstanz.</span><span class="sxs-lookup"><span data-stu-id="4002f-104">The list of loads per metric for for this application instance.</span></span> <span data-ttu-id="4002f-105">Für jede Metrik, die im definierte <see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" /> Anwendung erstellt oder aktualisiert wurde werden eine Instanz des <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" /> in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="4002f-105">For each metric that was defined in <see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" /> when application was created or updated there will be one instance of <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" /> in this list.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="4002f-106">Für Anwendungen, die keine Anwendungskapazität definiert wird diese Liste leer sein.</span><span class="sxs-lookup"><span data-stu-id="4002f-106">For applications that do not have application capacity defined this list will be empty.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodes">
      <MemberSignature Language="C#" Value="public long MaximumNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaximumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.MaximumNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumNodes As Long" />
      <MemberSignature Language="F#" Value="member this.MaximumNodes : int64" Usage="System.Fabric.Query.ApplicationLoadInformation.MaximumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4002f-107">Ruft die maximale Anzahl von Knoten, in denen diese Anwendung instanziiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="4002f-107">Gets the maximum number of nodes where this application can be instantiated.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="4002f-108">Anzahl der Knoten, die diese Anwendung zulässig ist, umfassen.</span><span class="sxs-lookup"><span data-stu-id="4002f-108">Number of nodes this application is allowed to span.</span></span>
            <span data-ttu-id="4002f-109">Dieser Wert ist gleich <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> festgelegt wurde, wenn die Anwendung erstellt oder aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="4002f-109">This value is equal to <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> that was set when application was created or updated.</span></span>
            </para>
        </value>
        <remarks>
            <span data-ttu-id="4002f-110">Für Anwendungen, die keine Anwendungskapazität definiert wird dieser Wert 0 (null) sein.</span><span class="sxs-lookup"><span data-stu-id="4002f-110">For applications that do not have application capacity defined this value will be zero.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodes">
      <MemberSignature Language="C#" Value="public long MinimumNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MinimumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.MinimumNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimumNodes As Long" />
      <MemberSignature Language="F#" Value="member this.MinimumNodes : int64" Usage="System.Fabric.Query.ApplicationLoadInformation.MinimumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4002f-111">Ruft die minimale Anzahl von Knoten für diese Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="4002f-111">Gets the minimum number of nodes for this application.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="4002f-112">Anzahl der Knoten, auf dem Service Fabric Kapazität im Cluster für diese Anwendungsinstanz reservieren.</span><span class="sxs-lookup"><span data-stu-id="4002f-112">Number of nodes where Service Fabric will reserve Capacity in the cluster for this Application instance.</span></span>
            <span data-ttu-id="4002f-113">Dieser Wert ist gleich <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" /> festgelegt wurde, wenn die Anwendung erstellt oder aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="4002f-113">This value is equal to <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" /> that was set when the application was created or updated.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Query.ApplicationLoadInformation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4002f-114">Ruft den Namen der Anwendung ab oder legt diesen fest.</span><span class="sxs-lookup"><span data-stu-id="4002f-114">Gets or sets the name of the application.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4002f-115">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="4002f-115">The name of the application.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeCount">
      <MemberSignature Language="C#" Value="public long NodeCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.NodeCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeCount As Long" />
      <MemberSignature Language="F#" Value="member this.NodeCount : int64" Usage="System.Fabric.Query.ApplicationLoadInformation.NodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4002f-116">Ruft die Anzahl der Knoten, auf denen diese Anwendung instanziiert wird.</span><span class="sxs-lookup"><span data-stu-id="4002f-116">Gets the number of nodes on which this application is instantiated.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="4002f-117">Die Anzahl der Knoten, auf denen diese Anwendung derzeit instanziiert wird.</span><span class="sxs-lookup"><span data-stu-id="4002f-117">The number of nodes on which this application is currently instantiated.</span></span>
            </para>
        </value>
        <remarks>
            <span data-ttu-id="4002f-118">Für Anwendungen, die keine Anwendungskapazität definiert wird dieser Wert 0 (null) sein.</span><span class="sxs-lookup"><span data-stu-id="4002f-118">For applications that do not have application capacity defined this value will be zero.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationLoadInformation.ToString " />
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
          <para>
            <span data-ttu-id="4002f-119">Details der Schöndruck <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="4002f-119">Pretty print out details of <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</span></span>
            </para>
        </summary>
        <returns><span data-ttu-id="4002f-120">Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="4002f-120">A string representation of the <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <example>
            <span data-ttu-id="4002f-121">"Parameter" ApplicationName "": "Fabric: / LoadBalancingAppType", "MinimumNodes": 0, "MaximumNodes": 0, "nodename": 0, "ApplicationLoadMetricInformation":]</span><span class="sxs-lookup"><span data-stu-id="4002f-121">"ApplicationName": "fabric:/LoadBalancingAppType", "MinimumNodes": 0, "MaximumNodes": 0, "NodeCount": 0, "ApplicationLoadMetricInformation": [],</span></span>
            </example>
      </Docs>
    </Member>
  </Members>
</Type>