<Type Name="ChaosReport" FullName="System.Fabric.Chaos.DataStructures.ChaosReport">
  <TypeSignature Language="C#" Value="public sealed class ChaosReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ChaosReport extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.ChaosReport" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ChaosReport" />
  <TypeSignature Language="F#" Value="type ChaosReport = class" />
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
      <para>Stellt den Status der ausgeführten Chaos, möglicherweise innerhalb eines Zeitraums von zurückgegeben <see cref="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter,System.TimeSpan,System.Threading.CancellationToken)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosReport (System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, System.Fabric.Chaos.DataStructures.ChaosStatus status, System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt; history, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, valuetype System.Fabric.Chaos.DataStructures.ChaosStatus status, class System.Collections.Generic.List`1&lt;class System.Fabric.Chaos.DataStructures.ChaosEvent&gt; history, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosReport.#ctor(System.Fabric.Chaos.DataStructures.ChaosParameters,System.Fabric.Chaos.DataStructures.ChaosStatus,System.Collections.Generic.List{System.Fabric.Chaos.DataStructures.ChaosEvent},System.String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosReport : System.Fabric.Chaos.DataStructures.ChaosParameters * System.Fabric.Chaos.DataStructures.ChaosStatus * System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt; * string -&gt; System.Fabric.Chaos.DataStructures.ChaosReport" Usage="new System.Fabric.Chaos.DataStructures.ChaosReport (chaosParameters, status, history, continuationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="chaosParameters" Type="System.Fabric.Chaos.DataStructures.ChaosParameters" />
        <Parameter Name="status" Type="System.Fabric.Chaos.DataStructures.ChaosStatus" />
        <Parameter Name="history" Type="System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt;" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="chaosParameters">Parameter, die mit denen Chaos gestartet wurde</param>
        <param name="status">Wenn Chaos derzeit ausgeführt wird oder beendet wird.</param>
        <param name="history">Die Liste der ChaosEvent's, erfüllen die ChaosReportFilter in ChaosParameters</param>
        <param name="continuationToken">Wenn zu viele Ereignisse der ChaosReportFilter übereinstimmen, die in mehreren Batches zurückgegeben, die Batches durch dieses Token verknüpft sind.</param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChaosParameters">
      <MemberSignature Language="C#" Value="public System.Fabric.Chaos.DataStructures.ChaosParameters ChaosParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Chaos.DataStructures.ChaosParameters ChaosParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosReport.ChaosParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ChaosParameters As ChaosParameters" />
      <MemberSignature Language="F#" Value="member this.ChaosParameters : System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="System.Fabric.Chaos.DataStructures.ChaosReport.ChaosParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Chaos.DataStructures.ChaosParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Parameter, die übergeben wurde, <see cref="M:System.Fabric.FabricClient.TestManagementClient.StartChaosAsync(System.Fabric.Chaos.DataStructures.ChaosParameters,System.TimeSpan,System.Threading.CancellationToken)" /> und mit dem Chaos gestartet wurde.</para>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosReport.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string" Usage="System.Fabric.Chaos.DataStructures.ChaosReport.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Wenn die Anzahl der Ereignisse Chaos zu groß ist, werden diese in Batches zurückgegeben; um dem nächsten Batch von Ereignissen der ContinuationToken abzurufen müssen daher in der API-Aufruf übergeben <see cref="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="History">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt; History { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.List`1&lt;class System.Fabric.Chaos.DataStructures.ChaosEvent&gt; History" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosReport.History" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property History As List(Of ChaosEvent)" />
      <MemberSignature Language="F#" Value="member this.History : System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt;" Usage="System.Fabric.Chaos.DataStructures.ChaosReport.History" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Chaos-Ereignisse, die im Zeitraum von Interesse, die im angegebenen erzeugt wurden <see cref="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter,System.TimeSpan,System.Threading.CancellationToken)" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public System.Fabric.Chaos.DataStructures.ChaosStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Chaos.DataStructures.ChaosStatus Status" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosReport.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As ChaosStatus" />
      <MemberSignature Language="F#" Value="member this.Status : System.Fabric.Chaos.DataStructures.ChaosStatus" Usage="System.Fabric.Chaos.DataStructures.ChaosReport.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Chaos.DataStructures.ChaosStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die aktuelle Aufgabe (eines Enumeratoren in CurrentChaosTask <c>Enum</c>), die Chaos ausführt.</para>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosReport.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="chaosReport.ToString " />
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
            Ruft eine Zeichenfolgendarstellung des Objekts Chaos Status ab.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des Objekts Chaos Status.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>