<Type Name="ApplicationHealthStateChunk" FullName="System.Fabric.Health.ApplicationHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthStateChunk" />
  <TypeSignature Language="F#" Value="type ApplicationHealthStateChunk = class" />
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
            Stellt eine Anwendung Health Status Segment, das grundlegende Zustandsinformationen zur Anwendung enthält.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.ApplicationHealthStateChunk.ApplicationName" />
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
            Ruft den Namen der Anwendung ab.
            </summary>
        <value>Der Anwendungsname.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Health.ApplicationHealthStateChunk.ApplicationTypeName" />
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
            Ruft den Typnamen der Anwendung ab.
            </summary>
        <value>Der Name des Anwendungstyps.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedApplicationHealthStateChunkList DeployedApplicationHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedApplicationHealthStateChunkList DeployedApplicationHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.DeployedApplicationHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationHealthStateChunks As DeployedApplicationHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationHealthStateChunks : System.Fabric.Health.DeployedApplicationHealthStateChunkList" Usage="System.Fabric.Health.ApplicationHealthStateChunk.DeployedApplicationHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedApplicationHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der bereitgestellten Anwendung Health Status Blöcke, die die Eingabefilter berücksichtigen.
            </summary>
        <value>Die Liste der bereitgestellten Anwendung Health Status Blöcke, die die Eingabefilter berücksichtigen.</value>
        <remarks>
          <para>Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten. Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen. Beispielsweise können Benutzer auf alle bereitgestellte Anwendungen enthalten ist, Status Integritätsfehler anfordern.
            Unabhängig von den Filterwert werden alle untergeordneten Elemente aggregiert Anwendungsintegrität berechnet verwendet.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.ApplicationHealthStateChunk.HealthState" />
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
            Ruft die Anwendung Integritätsstatus, berechnet aggregiert basierend auf alle gemeldeten integritätsereignisse, die untergeordneten Elemente und einer anwendungsintegritäts-Richtlinie.
            </summary>
        <value>Der Integritätsstatus der Anwendung aggregiert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceHealthStateChunkList ServiceHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceHealthStateChunkList ServiceHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.ServiceHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHealthStateChunks As ServiceHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.ServiceHealthStateChunks : System.Fabric.Health.ServiceHealthStateChunkList" Usage="System.Fabric.Health.ApplicationHealthStateChunk.ServiceHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der dienstintegrität Zustand Segmente, die die Eingabefilter berücksichtigen.
            </summary>
        <value>Die Liste der Service Health Status Blöcke, die die Eingabefilter berücksichtigen.</value>
        <remarks>
          <para>Standardmäßig sind keine untergeordneten Elemente in den Ergebnissen enthalten. Benutzer können anfordern, einige untergeordnete Elemente basierend auf den gewünschten Zustand oder andere Informationen einschließen. Beispielsweise können Benutzer auf alle Dienste enthalten ist, Status Integritätsfehler anfordern.
            Unabhängig von den Filterwert werden alle untergeordneten Elemente aggregiert Anwendungsintegrität berechnet verwendet.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthStateChunk.ToString " />
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