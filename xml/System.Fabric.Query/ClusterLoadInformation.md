<Type Name="ClusterLoadInformation" FullName="System.Fabric.Query.ClusterLoadInformation">
  <TypeSignature Language="C#" Value="public class ClusterLoadInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterLoadInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ClusterLoadInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterLoadInformation" />
  <TypeSignature Language="F#" Value="type ClusterLoadInformation = class" />
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
      <para><span data-ttu-id="0dac1-101">Stellt die Clusterinformationen für den Auslastungstest an.</span><span class="sxs-lookup"><span data-stu-id="0dac1-101">Represents the cluster load information.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterLoadInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ClusterLoadInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="0dac1-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.ClusterLoadInformation" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0dac1-102">Initializes a new instance of the <see cref="T:System.Fabric.Query.ClusterLoadInformation" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBalancingEndTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastBalancingEndTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastBalancingEndTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ClusterLoadInformation.LastBalancingEndTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastBalancingEndTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastBalancingEndTimeUtc : DateTime" Usage="System.Fabric.Query.ClusterLoadInformation.LastBalancingEndTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0dac1-103">Ruft die Endzeit der letzten Ressourcenausgleich ausführen (in UTC) ab.</span><span class="sxs-lookup"><span data-stu-id="0dac1-103">Gets the end time (in UTC) of last resource balancing run.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0dac1-104">Führen Sie die Endzeit der letzten Ressourcenausgleich zu können aus.</span><span class="sxs-lookup"><span data-stu-id="0dac1-104">The end time of last resource balancing run.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBalancingStartTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastBalancingStartTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastBalancingStartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ClusterLoadInformation.LastBalancingStartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastBalancingStartTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastBalancingStartTimeUtc : DateTime" Usage="System.Fabric.Query.ClusterLoadInformation.LastBalancingStartTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0dac1-105">Ruft die Startzeit des letzten Ressourcenausgleich ausführen (in UTC) ab.</span><span class="sxs-lookup"><span data-stu-id="0dac1-105">Gets the starting time (in UTC) of last resource balancing run.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0dac1-106">Führen Sie die Startzeit des letzten Ressourcenausgleich zu können aus.</span><span class="sxs-lookup"><span data-stu-id="0dac1-106">The starting time of last resource balancing run.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadMetricInformationList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricInformation&gt; LoadMetricInformationList { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.LoadMetricInformation&gt; LoadMetricInformationList" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ClusterLoadInformation.LoadMetricInformationList" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadMetricInformationList As IList(Of LoadMetricInformation)" />
      <MemberSignature Language="F#" Value="member this.LoadMetricInformationList : System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricInformation&gt;" Usage="System.Fabric.Query.ClusterLoadInformation.LoadMetricInformationList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0dac1-107">Ruft eine Liste der Auslastungstest Metriken Informationsobjekt ab.</span><span class="sxs-lookup"><span data-stu-id="0dac1-107">Gets a list of load metrics information object.</span></span> <span data-ttu-id="0dac1-108">Jeder Eintrag ist für eine bestimmte Metrik.</span><span class="sxs-lookup"><span data-stu-id="0dac1-108">Each entry is for a certain metrics.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0dac1-109">Eine Liste der Metriken-Informationsobjekt laden.</span><span class="sxs-lookup"><span data-stu-id="0dac1-109">A list of load metrics information object.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ClusterLoadInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterLoadInformation.ToString " />
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
            <span data-ttu-id="0dac1-110">Details der Schöndruck <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="0dac1-110">Pretty print out details of <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span></span>
            </para>
        </summary>
        <returns><span data-ttu-id="0dac1-111">Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="0dac1-111">A string representation of the <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <example>
            <span data-ttu-id="0dac1-112">LastBalancingStartTimeUtc: 11/9/2015 8:40:35 PM LastBalancingEndTimeUtc: 9/11/2015 8:40:35 PM LoadMetricInformation: LoadMetricName: Metric1 IsBalancedBefore: "true" IsBalancedAfter: "true" DeviationBefore: 2 DeviationAfter: 2 Balanci NgThreshold: 1-Aktion: NoActionNeeded ActivityThreshold: 3 ClusterCapacity: 100 ClusterLoad: 1 ClusterRemainingCapacity: NodeBufferPercentage 0: 0 ClusterBufferedCapacity: ClusterRemainingBufferedCapacity 0: 0 ClusterCapacityViolation: Tr UE MinNodeLoadValue: 0 MinNodeLoadNodeId: 1ca9521d70301383417536df0c96f671 MaxNodeLoadValue: 1 MaxNodeLoadNodeId: cf68563e16a44f808e86197a9cf83de5</span><span class="sxs-lookup"><span data-stu-id="0dac1-112">LastBalancingStartTimeUtc : 11/9/2015 8:40:35 PM LastBalancingEndTimeUtc   : 11/9/2015 8:40:35 PM LoadMetricInformation     : LoadMetricName        : Metric1 IsBalancedBefore      : True IsBalancedAfter       : True DeviationBefore       : 2 DeviationAfter        : 2 BalancingThreshold    : 1 Action    : NoActionNeeded ActivityThreshold     : 3 ClusterCapacity       : 100 ClusterLoad           : 1 ClusterRemainingCapacity : 0 NodeBufferPercentage  : 0 ClusterBufferedCapacity : 0 ClusterRemainingBufferedCapacity : 0 ClusterCapacityViolation : True MinNodeLoadValue      : 0 MinNodeLoadNodeId     : 1ca9521d70301383417536df0c96f671 MaxNodeLoadValue      : 1 MaxNodeLoadNodeId     : cf68563e16a44f808e86197a9cf83de5</span></span>
            </example>
      </Docs>
    </Member>
  </Members>
</Type>