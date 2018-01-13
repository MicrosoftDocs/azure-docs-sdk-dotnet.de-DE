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
      <para>Stellt die Clusterinformationen für den Auslastungstest an.</para>
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
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.ClusterLoadInformation" />-Klasse.</para>
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
          <para>Ruft die Endzeit der letzten Ressourcenausgleich ausführen (in UTC) ab.</para>
        </summary>
        <value>
          <para>Führen Sie die Endzeit der letzten Ressourcenausgleich zu können aus.</para>
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
          <para>Ruft die Startzeit des letzten Ressourcenausgleich ausführen (in UTC) ab.</para>
        </summary>
        <value>
          <para>Führen Sie die Startzeit des letzten Ressourcenausgleich zu können aus.</para>
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
          <para>Ruft eine Liste der Auslastungstest Metriken Informationsobjekt ab. Jeder Eintrag ist für eine bestimmte Metrik.</para>
        </summary>
        <value>
          <para>Eine Liste der Metriken-Informationsobjekt laden.</para>
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
            Details der Schöndruck <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.
            </para>
        </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</returns>
        <remarks>To be added.</remarks>
        <example>
            LastBalancingStartTimeUtc: 11/9/2015 8:40:35 PM LastBalancingEndTimeUtc: 9/11/2015 8:40:35 PM LoadMetricInformation: LoadMetricName: Metric1 IsBalancedBefore: "true" IsBalancedAfter: "true" DeviationBefore: 2 DeviationAfter: 2 Balanci NgThreshold: 1-Aktion: NoActionNeeded ActivityThreshold: 3 ClusterCapacity: 100 ClusterLoad: 1 ClusterRemainingCapacity: NodeBufferPercentage 0: 0 ClusterBufferedCapacity: ClusterRemainingBufferedCapacity 0: 0 ClusterCapacityViolation: Tr UE MinNodeLoadValue: 0 MinNodeLoadNodeId: 1ca9521d70301383417536df0c96f671 MaxNodeLoadValue: 1 MaxNodeLoadNodeId: cf68563e16a44f808e86197a9cf83de5
            </example>
      </Docs>
    </Member>
  </Members>
</Type>