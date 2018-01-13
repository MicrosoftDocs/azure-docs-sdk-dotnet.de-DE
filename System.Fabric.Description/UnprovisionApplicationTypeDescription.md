<Type Name="UnprovisionApplicationTypeDescription" FullName="System.Fabric.Description.UnprovisionApplicationTypeDescription">
  <TypeSignature Language="C#" Value="public sealed class UnprovisionApplicationTypeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UnprovisionApplicationTypeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.UnprovisionApplicationTypeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UnprovisionApplicationTypeDescription" />
  <TypeSignature Language="F#" Value="type UnprovisionApplicationTypeDescription = class" />
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
      <para>Beschreibt einen Anwendungstyp, die mithilfe von aufgehoben.%12%0 werden <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.Fabric.Description.UnprovisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UnprovisionApplicationTypeDescription (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UnprovisionApplicationTypeDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationTypeName As String, applicationTypeVersion As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.UnprovisionApplicationTypeDescription : string * string -&gt; System.Fabric.Description.UnprovisionApplicationTypeDescription" Usage="new System.Fabric.Description.UnprovisionApplicationTypeDescription (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Name des Anwendungstyps Bereitstellung</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die anwendungstypversion Bereitstellung</para>
        </param>
        <summary>
          <para>Instanziiert eine Instanz des <see cref="T:System.Fabric.Description.UnprovisionApplicationTypeDescription" />.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeName" />
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
          <para>Ruft ab, der Name des Anwendungstyps Bereitstellung.</para>
        </summary>
        <value>
          <para>Der Name des Anwendungstyps.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersion : string" Usage="System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeVersion" />
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
          <para>Ruft die Version der Anwendung auf die Aufhebung der Bereitstellung ab.</para>
        </summary>
        <value>
          <para>Die Anwendungstypversion.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Async">
      <MemberSignature Language="C#" Value="public bool Async { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Async" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UnprovisionApplicationTypeDescription.Async" />
      <MemberSignature Language="VB.NET" Value="Public Property Async As Boolean" />
      <MemberSignature Language="F#" Value="member this.Async : bool with get, set" Usage="System.Fabric.Description.UnprovisionApplicationTypeDescription.Async" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt das Flag, das angibt, ob die Aufhebung der Bereitstellung asynchron erfolgen soll.</para>
        </summary>
        <value>
          <para>Wenn dieses Flag auf "false" festgelegt ist, und klicken Sie dann das Verhalten dem Aufruf entspricht <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />. Der Timeout-Argument, das Aufheben der Bereitstellung-Vorgang selbst angewendet wird, und die zurückgegebene Aufgabe abgeschlossen ist, nur wenn das Aufheben der Bereitstellung Abschluss des Vorgangs im System.</para>
          <para>Wenn dieses Flag "true ist", klicken Sie dann das Timeout-Argument nur, um die Nachrichtenübermittlung angewendet wird und die zurückgegebene Aufgabe abgeschlossen, einmal ist hat das System die Anforderung akzeptiert. Das System verarbeitet den Vorgang das Aufheben der Bereitstellung unbegrenztes Timeout und seinen Status kann abgefragt werden, mithilfe von <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>