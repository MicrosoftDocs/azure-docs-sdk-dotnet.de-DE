<Type Name="ApplicationHealth" FullName="System.Fabric.Health.ApplicationHealth">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ApplicationHealth = class&#xA;    inherit EntityHealth" />
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
      <para>Die Integrität einer Anwendung beschrieben, wie vom <see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.ApplicationHealth.ApplicationName" />
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
          <para>Ruft den Anwendungsnamen, der die Anwendung eindeutig identifiziert. </para>
        </summary>
        <value>
          <para>Der Anwendungsname.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt; DeployedApplicationHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedApplicationHealthState&gt; DeployedApplicationHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.DeployedApplicationHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationHealthStates As IList(Of DeployedApplicationHealthState)" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt;" Usage="System.Fabric.Health.ApplicationHealth.DeployedApplicationHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Integritätsstatus der bereitgestellten Anwendung für die aktuelle Anwendung, die im Health Store.</para>
        </summary>
        <value>
          <para>bereitgestellten Anwendungen für die aktuelle Anwendung im Health Store gefunden.</para>
        </value>
        <remarks>To be added.</remarks>
        <para>Alle bereitgestellte Anwendungen werden ausgewertet, um zu bestimmen, die Anwendungsintegrität aggregiert.</para>
        <para>Nur Anwendungen bereitgestellt, die berücksichtigen die <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" /> (falls angegeben) werden zurückgegeben. Wenn der Filter nicht angegeben ist, werden alle bereitgestellte Anwendungen zurückgegeben.</para>
      </Docs>
    </Member>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.ApplicationHealth.HealthStatistics" />
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
            Ruft die Anwendung Integrität Statistiken, die enthalten Informationen darüber, wie viele Entitäten der Anwendung in werden <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.
            </summary>
        <value>Die Integrität Anwendungsstatistiken.</value>
        <remarks>
          <para>
            Die Integrität Anwendungsstatistiken enthalten Informationen über wie viele Dienste, Partitionen, Replikate, bereitgestellten Anwendungen und Pakete bereitgestellten Dienst sind in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, und <see cref="F:System.Fabric.Health.HealthState.Error" /> Zustand.
            Es kann null oder leer sein, wenn die Abfrage, die zurückgibt die <see cref="T:System.Fabric.Health.ApplicationHealth" /> angegebenen <see cref="T:System.Fabric.Health.ApplicationHealthStatisticsFilter" /> Health Statistiken ausschließen.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt; ServiceHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ServiceHealthState&gt; ServiceHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.ServiceHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHealthStates As IList(Of ServiceHealthState)" />
      <MemberSignature Language="F#" Value="member this.ServiceHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;" Usage="System.Fabric.Health.ApplicationHealth.ServiceHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die dienstintegritätszustände für die aktuelle Anwendung, die im Health Store.</para>
        </summary>
        <value>
          <para>Die Dienste von der aktuellen Anwendung als gefunden wurde im Health Store.</para>
        </value>
        <remarks>To be added.</remarks>
        <para>Alle Dienste werden ausgewertet, um zu bestimmen, die Anwendungsintegrität aggregiert.</para>
        <para>Dienste nur dieser Hinsicht mit der <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" /> (falls angegeben) werden zurückgegeben. Wenn der Filter nicht angegeben ist, werden alle Dienste zurückgegeben.</para>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealth.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der <see cref="T:System.Fabric.Health.ApplicationHealth" />.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.ApplicationHealth" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>