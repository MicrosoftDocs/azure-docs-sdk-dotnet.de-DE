<Type Name="ResolvedServicePartition" FullName="System.Fabric.ResolvedServicePartition">
  <TypeSignature Language="C#" Value="public sealed class ResolvedServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ResolvedServicePartition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ResolvedServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ResolvedServicePartition" />
  <TypeSignature Language="F#" Value="type ResolvedServicePartition = class" />
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
      <para>
            Enthält Informationen zur Partition des Diensts, der aufgelöst wurde und die Gruppe von Endpunkten, die Zugriff auf die Partition verwendet werden kann.</para>
    </summary>
    <remarks>
      <para>
            Die aufgelösten Dienstpartition abgerufen wird, als Ergebnis <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> und anderen Überladungen.
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CompareVersion">
      <MemberSignature Language="C#" Value="public int CompareVersion (System.Fabric.ResolvedServicePartition other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 CompareVersion(class System.Fabric.ResolvedServicePartition other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ResolvedServicePartition.CompareVersion(System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareVersion (other As ResolvedServicePartition) As Integer" />
      <MemberSignature Language="F#" Value="member this.CompareVersion : System.Fabric.ResolvedServicePartition -&gt; int" Usage="resolvedServicePartition.CompareVersion other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="other">
          <para>Die andere aufgelösten Dienstpartition, verglichen werden soll.</para>
        </param>
        <summary>
          <para>Vergleicht zwei aufgelösten Dienst Partitionen und identifiziert, die neuer ist. </para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Int32" />zurück.</para>
        </returns>
        <remarks>
          <para>Die <see cref="M:System.Fabric.ResolvedServicePartition.CompareVersion(System.Fabric.ResolvedServicePartition)" /> -Methode übernimmt ein Argument aufgelösten Dienst Partition (RSP), mit dem Parameter <paramref name="other" /> , damit der Benutzer aus, um zu ermitteln, die RSP mehr auf dem neuesten Stand ist. Ein Rückgabewert von 0 gibt an, dass die zwei RSPs die gleiche Version aufweisen. 1 gibt an, dass die anderen RSP eine ältere Version hat. -1 gibt an, dass die anderen RSP eine neuere Version aufweist. </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>Die beiden <see cref="T:System.Fabric.ResolvedServicePartition" /> Objekte aus anderen Dienst Partitionen sind. Dies kann geschehen, wenn der Dienst wird gelöscht und neu erstellt wird, mit dem gleichen Namen und die Trennung zwischen zwei lösen Aufrufe.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class System.Fabric.ResolvedServiceEndpoint&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As ICollection(Of ResolvedServiceEndpoint)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;" Usage="System.Fabric.ResolvedServicePartition.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Endpunkte der Dienstpartition ab.</para>
        </summary>
        <value>
          <para>Eine Auflistung von <see cref="T:System.Fabric.ResolvedServiceEndpoint" /> für die Partition angegebenen Dienst.</para>
        </value>
        <remarks>
          <para>Ein aufgelösten Dienstendpunkt enthält die Rolle der zustandsbehafteten dienstreplikats oder einer zustandslosen Dienstinstanz und die Adresse, in denen dieses Replikat erreicht werden kann.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServiceEndpoint GetEndpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.ResolvedServiceEndpoint GetEndpoint() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ResolvedServicePartition.GetEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoint () As ResolvedServiceEndpoint" />
      <MemberSignature Language="F#" Value="member this.GetEndpoint : unit -&gt; System.Fabric.ResolvedServiceEndpoint" Usage="resolvedServicePartition.GetEndpoint " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServiceEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Gibt einen einzelnen Endpunkt, anstatt eine Auflistung aller Endpunkte zurück. </para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Fabric.ResolvedServiceEndpoint" />zurück.</para>
        </returns>
        <remarks>
          <para>In vielen Fällen benötigen Sie nur einen einzigen Endpunkt anstelle aller Endpunkte. Wenn der Dienst, zustandslos ist, gibt es einen zufälligen Endpunkt zurück. Wenn der Dienst ein zustandsbehafteter Dienst ist als den Endpunkt zurückgegeben, den das primäre Replikat der Dienstpartition überwacht. Beachten Sie, dass das primäre Replikat derzeit nicht vorhanden ist, löst <see cref="T:System.Fabric.FabricException" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Info">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation Info { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation Info" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.Info" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Info As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.Info : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.ResolvedServicePartition.Info" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft Informationen zur Partition des Diensts, der gelöst wurde.</para>
        </summary>
        <value>Die Informationen zur Partition des Diensts, der behoben wurde.</value>
        <remarks>
          <para>
            Der Dienstpartition kann von anderen <see cref="T:System.Fabric.ServicePartitionKind" />.
            Sie können die Informationen zur Dienstpartition in den richtigen abgeleiteten Typ zum Abrufen von ausführliche Informationen zur Partition umwandeln.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.ResolvedServicePartition.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Namen der Dienstinstanz ab.</para>
        </summary>
        <value>
          <para>Der Name der Dienstinstanz.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>