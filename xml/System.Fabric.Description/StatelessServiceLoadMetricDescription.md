<Type Name="StatelessServiceLoadMetricDescription" FullName="System.Fabric.Description.StatelessServiceLoadMetricDescription">
  <TypeSignature Language="C#" Value="public sealed class StatelessServiceLoadMetricDescription : System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatelessServiceLoadMetricDescription extends System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatelessServiceLoadMetricDescription&#xA;Inherits ServiceLoadMetricDescription" />
  <TypeSignature Language="F#" Value="type StatelessServiceLoadMetricDescription = class&#xA;    inherit ServiceLoadMetricDescription" />
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
      <para><span data-ttu-id="c2c6d-101">Gibt eine Metrik für eines zustandslosen Diensts an.</span><span class="sxs-lookup"><span data-stu-id="c2c6d-101">Specifies a metric for a stateless service.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatelessServiceLoadMetricDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatelessServiceLoadMetricDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="c2c6d-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c2c6d-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultLoad">
      <MemberSignature Language="C#" Value="public int DefaultLoad { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DefaultLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatelessServiceLoadMetricDescription.DefaultLoad" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultLoad As Integer" />
      <MemberSignature Language="F#" Value="member this.DefaultLoad : int with get, set" Usage="System.Fabric.Description.StatelessServiceLoadMetricDescription.DefaultLoad" />
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
          <para><span data-ttu-id="c2c6d-103">Ruft ab oder Festlegen der Standarddauer der Auslastung, die diesen Dienst für die Metrik generiert wird.</span><span class="sxs-lookup"><span data-stu-id="c2c6d-103">Gets or sets the default amount of load that this service creates for this metric.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c2c6d-104">Die Standarddauer an der Auslastung, die diesen Dienst für die Metrik generiert wird.</span><span class="sxs-lookup"><span data-stu-id="c2c6d-104">The default amount of load that this service creates for this metric.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="c2c6d-105">Angeben von Standardwerten der Last für benutzerdefinierte Metriken kann Ressourcen-Manager von Service Fabric Cluster Services effizient zu platzieren, wenn sie zuerst erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="c2c6d-105">Specifying default load values for custom metrics enables the Service Fabric Cluster Resource Manager to efficiently place services when they are first created.</span></span>
            <span data-ttu-id="c2c6d-106">Wenn Standard Laden nicht angegeben, dass Service Fabric-Cluster-Ressourcen-Manager keine Last für dieses Replikat angenommen, bis der Dienst seine laden meldet.</span><span class="sxs-lookup"><span data-stu-id="c2c6d-106">If default load is not specified Service Fabric Cluster Resource Manager will assume zero load for this replica until the service reports its load.</span></span>
            <span data-ttu-id="c2c6d-107"><see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="c2c6d-107"><see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatelessServiceLoadMetricDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="statelessServiceLoadMetricDescription.ToString " />
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
            <span data-ttu-id="c2c6d-108">Details der Schöndruck <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />.</span><span class="sxs-lookup"><span data-stu-id="c2c6d-108">Pretty print out details of <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c2c6d-109">Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />.</span><span class="sxs-lookup"><span data-stu-id="c2c6d-109">A string representation of the <see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <example>
            <span data-ttu-id="c2c6d-110">CPU, hoch, 90</span><span class="sxs-lookup"><span data-stu-id="c2c6d-110">CPU,High,90</span></span>
            </example>
      </Docs>
    </Member>
  </Members>
</Type>