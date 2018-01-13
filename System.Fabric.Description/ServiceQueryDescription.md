<Type Name="ServiceQueryDescription" FullName="System.Fabric.Description.ServiceQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceQueryDescription" />
  <TypeSignature Language="F#" Value="type ServiceQueryDescription = class" />
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
      <para>Stellt dar, die mehrere Filter, die angegeben werden können, um die Rückgabe zu verfeinern.
            Wird von <see cref="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" /> verwendet.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceQueryDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceQueryDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceQueryDescription : Uri -&gt; System.Fabric.Description.ServiceQueryDescription" Usage="new System.Fabric.Description.ServiceQueryDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">To be added.</param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ServiceQueryDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ServiceQueryDescription.ApplicationName" />
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
          <para>Ruft den URI-Namen der Anwendung, die Dienste, bei der Abfrage enthält.</para>
        </summary>
        <value>
          <para>Der Name der URI der Anwendung, die Dienste, bei der Abfrage enthält.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ContinuationToken" />
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
          <para>Ruft ab oder legt das Token, das zum Abrufen der nächsten Seite von Abfragen verwendet werden kann.</para>
        </summary>
        <value>
          <para>Das Token, das zum Abrufen der nächsten Seite von Abfragen verwendet werden kann.</para>
        </value>
        <remarks>
          <para>ContinuationToken wird von einer vorherigen Abfrage empfangen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceNameFilter">
      <MemberSignature Language="C#" Value="public Uri ServiceNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ServiceNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceNameFilter : Uri with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ServiceNameFilter" />
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
          <para>Ruft ab oder legt den URI-Namen des Diensts bei der Abfrage.</para>
        </summary>
        <value>
          <para>Der Name der URI des Diensts zur Abfrage.</para>
        </value>
        <remarks>
          <para>ServiceNameFilter und ServiceTypeNameFilter können nicht zusammen angegeben werden.</para>
          <para>Wenn weder ServiceNameFilter noch ServiceTypeNameFilter angegeben wird, werden alle Dienste der angegebenen Anwendung zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ServiceTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ServiceTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeNameFilter : string with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ServiceTypeNameFilter" />
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
          <para>Ruft ab oder legt den Dienstnamen-Typ verwendet, um die Dienste für Abfragen zu filtern.
            Dienste, die dieses Diensttyps sind, werden zurückgegeben.</para>
        </summary>
        <value>
          <para>Der Diensttypname, der zum Filtern der Dienste verwendet wird, die abgefragt werden sollen.</para>
        </value>
        <remarks>
          <para>ServiceNameFilter und ServiceTypeNameFilter können nicht zusammen angegeben werden.</para>
          <para>Wenn weder ServiceNameFilter noch ServiceTypeNameFilter angegeben wird, werden alle Dienste der angegebenen Anwendung zurückgegeben.</para>
          <para>Dieser Filter ist Groß-/Kleinschreibung beachtet.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>