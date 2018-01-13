<Type Name="ServiceInstanceListener" FullName="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener">
  <TypeSignature Language="C#" Value="public sealed class ServiceInstanceListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceInstanceListener extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceInstanceListener" />
  <TypeSignature Language="F#" Value="type ServiceInstanceListener = class" />
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
            Stellt den Listener für die Kommunikation und die Eigenschaften für einen zustandslosen Dienstinstanz dar.
            Endpunkte, die vom Listener Kommunikation ausgegeben werden der Name des Listeners Kommunikation zugeordnet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceInstanceListener (Func&lt;System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; createCommunicationListener, string name = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class System.Fabric.StatelessServiceContext, class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; createCommunicationListener, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.#ctor(System.Func{System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createCommunicationListener As Func(Of StatelessServiceContext, ICommunicationListener), Optional name As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener : Func&lt;System.Fabric.StatelessServiceContext, Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; * string -&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener" Usage="new Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener (createCommunicationListener, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createCommunicationListener" Type="System.Func&lt;System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="createCommunicationListener">Factorymethode zum Erstellen des Listeners für die Kommunikation.</param>
        <param name="name">Der Name des Listeners Kommunikation. Dieser Parameter ist optional, wenn der statusfreien Dienst nur eine Kommunikation Listener verfügt. Wenn es nicht angegeben ist, wird der Name auf DefaultName festgelegt.</param>
        <summary>
            Initialisiert eine neue Instanz der ServiceInstanceListener an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCommunicationListener">
      <MemberSignature Language="C#" Value="public Func&lt;System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; CreateCommunicationListener { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class System.Fabric.StatelessServiceContext, class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; CreateCommunicationListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.CreateCommunicationListener" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreateCommunicationListener As Func(Of StatelessServiceContext, ICommunicationListener)" />
      <MemberSignature Language="F#" Value="member this.CreateCommunicationListener : Func&lt;System.Fabric.StatelessServiceContext, Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.CreateCommunicationListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Factorymethode zum Erstellen des Listeners für die Kommunikation ab.</para>
        </summary>
        <value>
          <para>Die Factorymethode zum Erstellen des Listeners für die Kommunikation.</para>
        </value>
        <remarks>
          <para>Die Factory-Methode akzeptiert eine <see cref="T:System.Fabric.StatelessServiceContext" /> und gibt Kommunikation Listener implementieren <see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultName">
      <MemberSignature Language="C#" Value="public const string DefaultName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.DefaultName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultName : string" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.DefaultName" />
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
          <para>Der Standardname des Listeners Service-Instanz.</para>
        </summary>
        <returns>
          <para>Der Standardname des Listeners Service-Instanz.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.Name" />
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