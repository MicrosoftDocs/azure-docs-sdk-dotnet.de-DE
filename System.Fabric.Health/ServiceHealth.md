<Type Name="ServiceHealth" FullName="System.Fabric.Health.ServiceHealth">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ServiceHealth = class&#xA;    inherit EntityHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Die Integrität eines Diensts beschreibt, wie vom <see cref="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.ServiceHealth.HealthStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Service Health Statistiken, die enthalten Informationen darüber, wie viele Partitionen und Replikaten in werden <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.
            </summary>
        <value>Die Statistiken für den Dienst-Integrität.</value>
        <remarks>
          <para>
            Das Service Health Statistiken enthalten Informationen über wie viele Partitionen und Replikate befinden sich im <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.
            Es kann null oder leer sein, wenn die Abfrage, die zurückgibt die <see cref="T:System.Fabric.Health.ServiceHealth" /> angegebenen <see cref="T:System.Fabric.Health.ServiceHealthStatisticsFilter" /> Health Statistiken ausschließen.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthState&gt; PartitionHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.PartitionHealthState&gt; PartitionHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealth.PartitionHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionHealthStates As IList(Of PartitionHealthState)" />
      <MemberSignature Language="F#" Value="member this.PartitionHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthState&gt;" Usage="System.Fabric.Health.ServiceHealth.PartitionHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Integritätsstatus Partition für den aktuellen Dienst ab.</para>
        </summary>
        <value>
          <para>Die Partition Integritätsstatus für den aktuellen Dienst.</para>
        </value>
        <remarks>
          <para>Nur Partitionen dieser Hinsicht mit der <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.PartitionsFilter" /> (falls angegeben) werden zurückgegeben. Wenn der Filter nicht angegeben ist, werden alle Partitionen zurückgegeben.</para>
          <para>Alle Partitionen werden ausgewertet, um die aggregierten Integrität zu ermitteln.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealth.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Health.ServiceHealth.ServiceName" />
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
          <para>Ruft den Dienstnamen, der die Service Health Entität eindeutig identifiziert.</para>
        </summary>
        <value>
          <para>Der Dienstname der Entität Health Service eindeutig identifiziert.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealth.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der <see cref="T:System.Fabric.Health.ServiceHealth" />.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.ServiceHealth" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>