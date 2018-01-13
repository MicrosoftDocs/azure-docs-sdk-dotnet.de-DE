<Type Name="ServiceReplicaListener" FullName="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener">
  <TypeSignature Language="C#" Value="public sealed class ServiceReplicaListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceReplicaListener extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceReplicaListener" />
  <TypeSignature Language="F#" Value="type ServiceReplicaListener = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Listener für die Kommunikation und die Eigenschaften für einen Zustandsbehafteten dienstreplikats darstellt.
            Endpunkte, die vom Listener Kommunikation ausgegeben werden der Name des Listeners Kommunikation zugeordnet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceReplicaListener (Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; createCommunicationListener, string name = &quot;&quot;, bool listenOnSecondary = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class System.Fabric.StatefulServiceContext, class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; createCommunicationListener, string name, bool listenOnSecondary) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.#ctor(System.Func{System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener},System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createCommunicationListener As Func(Of StatefulServiceContext, ICommunicationListener), Optional name As String = &quot;&quot;, Optional listenOnSecondary As Boolean = false)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener : Func&lt;System.Fabric.StatefulServiceContext, Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; * string * bool -&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" Usage="new Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener (createCommunicationListener, name, listenOnSecondary)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createCommunicationListener" Type="System.Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="listenOnSecondary" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="createCommunicationListener">Factorymethode zum Erstellen des Listeners Kommunikation</param>
        <param name="name">Der Name des Listeners Kommunikation. Dieser Parameter ist optional, wenn der Dienst nur eine Kommunikation Listener hat</param>
        <param name="listenOnSecondary">Gibt an, ob der Listener Kommunikation muss geöffnet werden, wenn das Replikat aktive sekundäre Datenbank wird. Dieser Parameter ist optional</param>
        <summary>
            Erstellt die ServiceReplicaListener
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCommunicationListener">
      <MemberSignature Language="C#" Value="public Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; CreateCommunicationListener { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class System.Fabric.StatefulServiceContext, class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; CreateCommunicationListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.CreateCommunicationListener" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreateCommunicationListener As Func(Of StatefulServiceContext, ICommunicationListener)" />
      <MemberSignature Language="F#" Value="member this.CreateCommunicationListener : Func&lt;System.Fabric.StatefulServiceContext, Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.CreateCommunicationListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Factorymethode zum Erstellen des Listeners für die Kommunikation ab.</para>
        </summary>
        <value>
          <para>Die Factorymethode zum Erstellen des Listeners für die Kommunikation.</para>
        </value>
        <remarks>
          <para>Die Factory-Methode akzeptiert eine <see cref="T:System.Fabric.StatefulServiceContext" /> und gibt Kommunikation Listener implementieren <see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultName">
      <MemberSignature Language="C#" Value="public const string DefaultName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.DefaultName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultName : string" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.DefaultName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Der Standardname des Dienst-Replikat-Listeners.</para>
        </summary>
        <returns>
          <para>Der Standardname des Dienst-Replikat-Listeners.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenOnSecondary">
      <MemberSignature Language="C#" Value="public bool ListenOnSecondary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ListenOnSecondary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.ListenOnSecondary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenOnSecondary As Boolean" />
      <MemberSignature Language="F#" Value="member this.ListenOnSecondary : bool" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.ListenOnSecondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft das Flag, das angibt, ob diese Kommunikation Listener geöffnet werden soll, wenn das Replikat wird ein <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />.</para>
          <para>Wenn dieses Elements auf "false" festgelegt ist, wird die Kommunikation Listener geöffnet, nur, wenn das Replikat wird <see cref="F:System.Fabric.ReplicaRole.Primary" />.</para>
          <para>Der Standardwert ist <languageKeyword>false</languageKeyword>.</para>
        </summary>
        <value>
          <para>Das Flag, das angibt, ob diese Kommunikation Listener geöffnet werden soll, wenn das Replikat ist <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />.</para>
        </value>
        <remarks>
          <para>Dieses Flag kann festgelegt werden, wenn das primäre Replikat ist ausgelastet und Lesevorgänge dienen und schreibt Sie effizient und die Anwendung Daten lesen, veraltete (jedoch konsistent) tolerieren kann, und klicken Sie dann die Daten vom sekundären Replikat gelesen werden können.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Namen des Listeners Kommunikation.</para>
        </summary>
        <value>
          <para>Der Name des Listeners Kommunikation.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>