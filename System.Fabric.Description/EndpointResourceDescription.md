<Type Name="EndpointResourceDescription" FullName="System.Fabric.Description.EndpointResourceDescription">
  <TypeSignature Language="C#" Value="public sealed class EndpointResourceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EndpointResourceDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.EndpointResourceDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EndpointResourceDescription" />
  <TypeSignature Language="F#" Value="type EndpointResourceDescription = class" />
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
      <para>Beschreibt die endpunktressource.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointResourceDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.EndpointResourceDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz von <see cref="T:System.Fabric.Description.EndpointResourceDescription" />.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public string Certificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Certificate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificate As String" />
      <MemberSignature Language="F#" Value="member this.Certificate : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.Certificate" />
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
          <para>Nicht verwenden. Diese Eigenschaft wird nicht unterstützt.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.String" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.CodePackageName" />
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
          <para>
            Ruft den Namen des Pakets für Code, der im Attribut CodePackageRef des endpunktressource im Dienstmanifest angegeben wurde.
            </para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.String" />zurück.</para>
        </value>
        <remarks>
            Wenn kein Attribut CodePackageRef im endpunktressource im Dienstmanifest angegeben wurde, ist dessen Wert die leere Zeichenfolge.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointType">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.EndpointType EndpointType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.EndpointType EndpointType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.EndpointType" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointType As EndpointType" />
      <MemberSignature Language="F#" Value="member this.EndpointType : System.Fabric.Description.EndpointType with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.EndpointType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.EndpointType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Typ des Endpunkts ab.</para>
        </summary>
        <value>
          <para>Der Typ des Endpunkts.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddressOrFqdn">
      <MemberSignature Language="C#" Value="public string IpAddressOrFqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddressOrFqdn" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.IpAddressOrFqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddressOrFqdn As String" />
      <MemberSignature Language="F#" Value="member this.IpAddressOrFqdn : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.IpAddressOrFqdn" />
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
          <para>
            Ruft die IP-Adresse dieses endpunktressource zugeordnet.
            </para>
        </summary>
        <value>
          <para>He IP-Adresse, die dieser endpunktressource zugeordneten zurückgegeben.</para>
        </value>
        <remarks>
          <para>
            Wenn CodePackageRef-Attribut in endpunktressource im Dienstmanifest und das referenzierte Codepaket angegeben wurde. <see cref="P:System.Fabric.Description.EndpointResourceDescription.CodePackageName" /> angegeben hatten, Netzwerkeinstellungen für die explizite IP-Adresszuweisung, dessen Wert ist die IP-Adresse, die durch dieses Codepaket zugewiesen wurde, Service Fabric-Laufzeit. In allen anderen Fällen ist der Wert der IP-Adresse (oder FQDN) des Computers, auf dem Dienst ausgeführt wird.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.Name" />
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
          <para>Ruft den Namen des Endpunkts ab oder legt diesen fest.</para>
        </summary>
        <value>
          <para>Der Name des Endpunkts.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathSuffix">
      <MemberSignature Language="C#" Value="public string PathSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathSuffix" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.PathSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property PathSuffix As String" />
      <MemberSignature Language="F#" Value="member this.PathSuffix : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.PathSuffix" />
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
          <para>Ruft das Pfadsuffix für den Endpunkt ab.</para>
        </summary>
        <value>
          <para>Das Pfadsuffix für Endpunkt wie /myapp1.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public int Port { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Port" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.Port" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Port As Integer" />
      <MemberSignature Language="F#" Value="member this.Port : int" Usage="System.Fabric.Description.EndpointResourceDescription.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Anschluss für diesen Endpunkt zugewiesen.</para>
        </summary>
        <value>
          <para>Der Port, der für diesen Endpunkt zugewiesen wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.EndpointProtocol Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.EndpointProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As EndpointProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : System.Fabric.Description.EndpointProtocol with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.EndpointProtocol</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die von diesem Endpunkt verwendete Protokoll ab.</para>
        </summary>
        <value>
          <para>Das von diesem Endpunkt verwendete Protokoll.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UriScheme">
      <MemberSignature Language="C#" Value="public string UriScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UriScheme" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.UriScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property UriScheme As String" />
      <MemberSignature Language="F#" Value="member this.UriScheme : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.UriScheme" />
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
          <para>Ruft das Uri-Schema für den Endpunkt ab.</para>
        </summary>
        <value>
          <para>Das Uri-Schema für den Endpunkt, wie z. B. http, Https ftp.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>