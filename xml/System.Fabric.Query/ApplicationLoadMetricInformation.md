<Type Name="ApplicationLoadMetricInformation" FullName="System.Fabric.Query.ApplicationLoadMetricInformation">
  <TypeSignature Language="C#" Value="public sealed class ApplicationLoadMetricInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationLoadMetricInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationLoadMetricInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationLoadMetricInformation" />
  <TypeSignature Language="F#" Value="type ApplicationLoadMetricInformation = class" />
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
            <span data-ttu-id="c5b9f-101">Stellt die Informationen zum Kapazität und der aktuellen Auslastung für eine Metrik, die Dienste der Anwendung verwenden.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-101">Represents the information about capacity and current load for one metric that services of the application are using.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationLoadMetricInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadMetricInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="c5b9f-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-102">Initializes a new instance of the <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationCapacity">
      <MemberSignature Language="C#" Value="public long ApplicationCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ApplicationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.ApplicationCapacity : int64" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationCapacity" />
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
            <span data-ttu-id="c5b9f-103">Ruft die gesamte Kapazität für die Metrik ab.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-103">Gets the total capacity for this metric.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c5b9f-104">Die gesamte Kapazität, die für die Metrik verfügbar ist, die die Dienste dieser Anwendung verwenden können.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-104">The total capacity that is available for this metric that the services of this application can use.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLoad">
      <MemberSignature Language="C#" Value="public long ApplicationLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ApplicationLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationLoad As Long" />
      <MemberSignature Language="F#" Value="member this.ApplicationLoad : int64" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationLoad" />
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
            <span data-ttu-id="c5b9f-105">Ruft die Last für die Metrik an.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-105">Gets the load for this metric.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c5b9f-106">Die Gesamtlast, die die Dienste dieser Anwendung verwenden.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-106">The total load that the services of this application are using.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.Name" />
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
            <span data-ttu-id="c5b9f-107">Ruft den Namen der Metrik.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-107">Gets the name of the metric.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c5b9f-108">Der Name der Metrik.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-108">The name of the metric.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReservationCapacity">
      <MemberSignature Language="C#" Value="public long ReservationCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReservationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.ReservationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReservationCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.ReservationCapacity : int64" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.ReservationCapacity" />
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
            <span data-ttu-id="c5b9f-109">Ruft die reservierte Kapazität für die Metrik ab.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-109">Gets the reserved capacity for this metric.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c5b9f-110">Die Ammount der Kapazität, der im Cluster für diese Anwendung reserviert ist.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-110">The ammount of capacity that is reserved in the cluster for this application.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadMetricInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationLoadMetricInformation.ToString " />
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
            <span data-ttu-id="c5b9f-111">Details der Schöndruck <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-111">Pretty print out details of <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" />.</span></span>
            </para>
        </summary>
        <returns><span data-ttu-id="c5b9f-112">Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c5b9f-112">A string representation of the <see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <example>
            <span data-ttu-id="c5b9f-113">LoadMetricName: Metric1 ReservationCapacity: ApplicationCapacity 10: 10 ApplicationLoad: 2</span><span class="sxs-lookup"><span data-stu-id="c5b9f-113">LoadMetricName        : Metric1 ReservationCapacity   : 10 ApplicationCapacity   : 10 ApplicationLoad       : 2</span></span>
            </example>
      </Docs>
    </Member>
  </Members>
</Type>