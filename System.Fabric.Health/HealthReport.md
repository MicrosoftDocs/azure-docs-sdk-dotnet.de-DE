<Type Name="HealthReport" FullName="System.Fabric.Health.HealthReport">
  <TypeSignature Language="C#" Value="public abstract class HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit HealthReport extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthReport" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class HealthReport" />
  <TypeSignature Language="F#" Value="type HealthReport = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.ApplicationHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.ClusterHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.NodeHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.PartitionHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.ServiceHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.StatelessServiceInstanceHealthReport))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.StatefulServiceReplicaHealthReport))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>Stellt eine Basisklasse für Integrität Bericht Klassen dar.</para>
    </summary>
    <remarks>
      <para>Unterstützten Typen von integritätsberichten sind:<list type="bullet"><item><description><see cref="T:System.Fabric.Health.ApplicationHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.ClusterHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.NodeHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.PartitionHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.ServiceHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.StatelessServiceInstanceHealthReport" /></description></item><item><description><see cref="T:System.Fabric.Health.StatefulServiceReplicaHealthReport" /></description></item></list></para>
      <para>Der Bericht kann gesendet werden, mit dem Health Store <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected HealthReport (System.Fabric.Health.HealthReportKind kind, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Health.HealthReportKind kind, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthReport.#ctor(System.Fabric.Health.HealthReportKind,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.HealthReport : System.Fabric.Health.HealthReportKind * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.HealthReport" Usage="new System.Fabric.Health.HealthReport (kind, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.Health.HealthReportKind" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para>Die Art der Integritätsbericht senden. </para>
        </param>
        <param name="healthInformation">
          <para>Die <see cref="T:System.Fabric.Health.HealthInformation" /> der beschrieben wird, die Berichtsfelder wie SourceId, Eigenschaft, Integritätsstatus. Erforderlich.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.HealthReport" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthInformation">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthInformation HealthInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthInformation HealthInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthReport.HealthInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthInformation As HealthInformation" />
      <MemberSignature Language="F#" Value="member this.HealthInformation : System.Fabric.Health.HealthInformation" Usage="System.Fabric.Health.HealthReport.HealthInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Zustandsinformationen, die allgemeine Integrität Felder beschreibt.</para>
        </summary>
        <value>
          <para>Die Zustandsinformationen, die allgemeine Integrität Felder beschreibt.</para>
        </value>
        <remarks>Die Zustandsinformationen wird beibehalten, im Health Store innerhalb der <see cref="T:System.Fabric.Health.HealthEvent" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthReportKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthReportKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthReport.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As HealthReportKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Health.HealthReportKind" Usage="System.Fabric.Health.HealthReport.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthReportKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Art des integritätsberichts ab.</para>
        </summary>
        <value>
          <para>Die Art der Integritätsbericht senden.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>