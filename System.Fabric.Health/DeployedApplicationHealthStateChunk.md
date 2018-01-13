<Type Name="DeployedApplicationHealthStateChunk" FullName="System.Fabric.Health.DeployedApplicationHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthStateChunk" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthStateChunk = class" />
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
            Stellt eine bereitgestellte Anwendung Health Status Block, die grundlegende Zustandsinformationen zur der bereitgestellten Anwendung enthält.
            Sie ist als untergeordnetes Element von einer Anwendung aus.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeployedServicePackageHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedServicePackageHealthStateChunkList DeployedServicePackageHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedServicePackageHealthStateChunkList DeployedServicePackageHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateChunk.DeployedServicePackageHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServicePackageHealthStateChunks As DeployedServicePackageHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackageHealthStateChunks : System.Fabric.Health.DeployedServicePackageHealthStateChunkList" Usage="System.Fabric.Health.DeployedApplicationHealthStateChunk.DeployedServicePackageHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedServicePackageHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der bereitgestellten Dienst Paket Integrität Zustand Blöcke untergeordneten Elemente, die die Eingabefilter berücksichtigen.
            </summary>
        <value>Die Liste der bereitgestellten Dienst Paket Replikat-Integritätsstatus Blöcken untergeordnete Elemente, die die Eingabefilter berücksichtigen.</value>
        <remarks>
          <para>Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten. Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen. Beispielsweise können Benutzer auf alle bereitgestellten dienstpakete enthalten ist, Status Integritätsfehler anfordern.
            Unabhängig von den Filterwert werden alle untergeordneten Elemente aggregiert Entitätsintegrität berechnet verwendet.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.DeployedApplicationHealthStateChunk.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, der aggregierte Integritätszustand der bereitgestellten Anwendung berechnet anhand alle gemeldeten integritätsereignisse, die untergeordneten Elemente und einer anwendungsintegritäts-Richtlinie.
            </summary>
        <value>Der aggregierte Integritätszustand der bereitgestellten Anwendung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateChunk.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedApplicationHealthStateChunk.NodeName" />
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
            Ruft den Knotennamen ab.
            </summary>
        <value>Der Knotenname.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthStateChunk.ToString " />
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
            Erstellt eine zeichenfolgenbeschreibung des Segments Status Integrität an.
            </summary>
        <returns>Die zeichenfolgenbeschreibung des Segments Status Integrität.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>