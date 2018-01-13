<Type Name="ServiceContext" FullName="System.Fabric.ServiceContext">
  <TypeSignature Language="C#" Value="public abstract class ServiceContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceContext" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceContext" />
  <TypeSignature Language="F#" Value="type ServiceContext = class" />
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
            Der Kontext, in denen der Dienst unter.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceContext (System.Fabric.NodeContext nodeContext, System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, Uri serviceName, byte[] initializationData, Guid partitionId, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.NodeContext nodeContext, class System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData, valuetype System.Guid partitionId, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceContext.#ctor(System.Fabric.NodeContext,System.Fabric.ICodePackageActivationContext,System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
      <MemberSignature Language="F#" Value="new System.Fabric.ServiceContext : System.Fabric.NodeContext * System.Fabric.ICodePackageActivationContext * string * Uri * byte[] * Guid * int64 -&gt; System.Fabric.ServiceContext" Usage="new System.Fabric.ServiceContext (nodeContext, codePackageActivationContext, serviceTypeName, serviceName, initializationData, partitionId, replicaOrInstanceId)" />
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
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeContext">Der Knotenkontext, der Informationen zum Knoten enthält, in die statusfreien Dienstinstanz ausgeführt wird.</param>
        <param name="codePackageActivationContext">Das Codepaket-Aktivierungskontext, das Informationen über das Dienstmanifest und das Paket derzeit aktivierten Code enthält, like Arbeitsverzeichnis Kontext-ID usw.</param>
        <param name="serviceTypeName">Der Diensttypname.</param>
        <param name="serviceName">Der Name des Diensts.</param>
        <param name="initializationData">Die Initialisierungsdaten Dienst, die angepasste Initialisierung von Daten durch den Ersteller des Diensts darstellt.</param>
        <param name="partitionId">Die Partitions-ID.</param>
        <param name="replicaOrInstanceId">Das Replikat oder eine Instanz-ID an.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.ServiceContext" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageActivationContext">
      <MemberSignature Language="C#" Value="public System.Fabric.ICodePackageActivationContext CodePackageActivationContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ICodePackageActivationContext CodePackageActivationContext" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.CodePackageActivationContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageActivationContext As ICodePackageActivationContext" />
      <MemberSignature Language="F#" Value="member this.CodePackageActivationContext : System.Fabric.ICodePackageActivationContext" Usage="System.Fabric.ServiceContext.CodePackageActivationContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ICodePackageActivationContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft das Codepaket-Aktivierungskontext, das Informationen über das Dienstmanifest und das Paket derzeit aktivierten Code enthält, like Arbeitsverzeichnis Kontext-ID usw.</para>
        </summary>
        <value>Das Codepaket-Aktivierungskontext.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[]" Usage="System.Fabric.ServiceContext.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Initialisierungsdaten des Diensts ab.
            </summary>
        <value>Die Initialisierungsdaten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenAddress">
      <MemberSignature Language="C#" Value="public string ListenAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ListenAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ListenAddress : string" Usage="System.Fabric.ServiceContext.ListenAddress" />
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
          <para>Die Adresse, an der den Listener für die Kommunikation der Dienst gestartet werden soll.</para>
        </summary>
        <value>
          <para>Die Adresse, an der den Listener für die Kommunikation der Dienst gestartet werden soll.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeContext">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeContext NodeContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeContext NodeContext" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.NodeContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeContext As NodeContext" />
      <MemberSignature Language="F#" Value="member this.NodeContext : System.Fabric.NodeContext" Usage="System.Fabric.ServiceContext.NodeContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die vom Knotenkontext mit Informationen über den Knoten, in dem das Replikat Dienst instanziiert wird.
            </summary>
        <value>Der Knotenkontext für den Knoten, in dem die dienstreplikats oder die Instanz instanziiert wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.ServiceContext.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Partitions-ID.
            </summary>
        <value>Die Partitions-ID.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishAddress">
      <MemberSignature Language="C#" Value="public string PublishAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.PublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.PublishAddress : string" Usage="System.Fabric.ServiceContext.PublishAddress" />
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
          <para>Die Adresse, die der Dienst als die abhöradresse veröffentlichen.</para>
        </summary>
        <value>
          <para>Die Adresse, die der Dienst als die abhöradresse veröffentlichen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceId">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ReplicaOrInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaOrInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceId : int64" Usage="System.Fabric.ServiceContext.ReplicaOrInstanceId" />
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
            Ruft ab, der einem zustandsbehafteten Dienst dienstreplikats oder die ID der statusfreien Dienstinstanz-ID
            </summary>
        <value>Die Replikat-ID mit einem zustandsbehafteten Dienst oder der statusfreien Dienstinstanz-ID auf.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.ServiceContext.ServiceName" />
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
            Ruft den Dienstnamen.
            </summary>
        <value>Der Name des Diensts.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.ServiceContext.ServiceTypeName" />
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
            Ruft den Typnamen des Dienstes ab.
            </summary>
        <value>Der Diensttypname.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TraceId">
      <MemberSignature Language="C#" Value="public string TraceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TraceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.TraceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TraceId As String" />
      <MemberSignature Language="F#" Value="member this.TraceId : string" Usage="System.Fabric.ServiceContext.TraceId" />
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
            Ruft die Ablaufverfolgungs-ID des Diensts ab.
            </summary>
        <value>Die Ablaufverfolgungs-ID des Diensts.</value>
        <remarks>Für alle generierten ablaufverfolgungen kann die Ablaufverfolgungs-ID als Bezeichner verwendet werden.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>