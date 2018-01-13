<Type Name="StatefulServiceContext" FullName="System.Fabric.StatefulServiceContext">
  <TypeSignature Language="C#" Value="public sealed class StatefulServiceContext : System.Fabric.ServiceContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServiceContext extends System.Fabric.ServiceContext" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.StatefulServiceContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServiceContext&#xA;Inherits ServiceContext" />
  <TypeSignature Language="F#" Value="type StatefulServiceContext = class&#xA;    inherit ServiceContext" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.ServiceContext</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt den Kontext, in denen der zustandsbehaftete Dienst unter dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceContext (System.Fabric.NodeContext nodeContext, System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, Uri serviceName, byte[] initializationData, Guid partitionId, long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.NodeContext nodeContext, class System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData, valuetype System.Guid partitionId, int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.StatefulServiceContext.#ctor(System.Fabric.NodeContext,System.Fabric.ICodePackageActivationContext,System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
      <MemberSignature Language="F#" Value="new System.Fabric.StatefulServiceContext : System.Fabric.NodeContext * System.Fabric.ICodePackageActivationContext * string * Uri * byte[] * Guid * int64 -&gt; System.Fabric.StatefulServiceContext" Usage="new System.Fabric.StatefulServiceContext (nodeContext, codePackageActivationContext, serviceTypeName, serviceName, initializationData, partitionId, replicaId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeContext" Type="System.Fabric.NodeContext" />
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.ICodePackageActivationContext" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeContext">Der Knotenkontext, der Informationen zum Knoten enthält, in die statusfreien Dienstinstanz ausgeführt wird.</param>
        <param name="codePackageActivationContext">Das Codepaket-Aktivierungskontext, das Informationen über das Dienstmanifest und das Paket derzeit aktivierten Code enthält, like Arbeitsverzeichnis Kontext-ID usw.</param>
        <param name="serviceTypeName">Der Diensttypname.</param>
        <param name="serviceName">Der Name des Diensts.</param>
        <param name="initializationData">Die Initialisierungsdaten Dienst, die angepasste Initialisierung von Daten durch den Ersteller des Diensts darstellt.</param>
        <param name="partitionId">Die Partitions-ID.</param>
        <param name="replicaId">Die Replikat-ID</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.StatefulServiceContext" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.StatefulServiceContext.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.StatefulServiceContext.ReplicaId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die einem zustandsbehafteten Dienst Replikat-ID ab.
            </summary>
        <value>Der zustandsbehaftete Dienst Replikat-ID an.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>