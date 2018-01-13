<Type Name="ConnectionMode" FullName="Microsoft.Azure.Documents.Client.ConnectionMode">
  <TypeSignature Language="C#" Value="public enum ConnectionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.ConnectionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectionMode" />
  <TypeSignature Language="F#" Value="type ConnectionMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Stellt den Verbindungsmodus auf die vom Client verwendet werden, wenn eine Verbindung mit der Azure-Cosmos-DB-Dienst herstellen.
            </summary>
    <remarks>
            Gateway Konnektivität Modi "und" Direct werden unterstützt. Gateway ist die Standardeinstellung. 
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.Client.ConnectionPolicy" />
    <altmember cref="T:Microsoft.Azure.Documents.Client.Protocol" />
    <example>
      <code language="c#"><![CDATA[
            DocumentClient client = new DocumentClient(endpointUri, masterKey, new ConnectionPolicy { ConnectionMode = ConnectionMode.Direct });
            ]]></code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="Direct">
      <MemberSignature Language="C#" Value="Direct" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.ConnectionMode Direct = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.ConnectionMode.Direct" />
      <MemberSignature Language="VB.NET" Value="Direct" />
      <MemberSignature Language="F#" Value="Direct = 1" Usage="Microsoft.Azure.Documents.Client.ConnectionMode.Direct" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Client.ConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Verwendet direkte Verbindung mit der Datenknoten im Azure-Cosmos-DB-Dienst herstellen. Gateway nur zu initialisieren und Cache logischen Adressen verwendet werden, und aktualisieren Sie auf updates
            </summary>
        <remarks>
            Verwenden Sie direkten Konnektivität für optimale Leistung zu erzielen. Auf den Datenknoten auf Azure Cosmos-DB-Clustern für einen Bereich von Portnummern Verbindungen hergestellt werden, entweder über HTTPS oder TCP/SSL.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Gateway">
      <MemberSignature Language="C#" Value="Gateway" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.ConnectionMode Gateway = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.ConnectionMode.Gateway" />
      <MemberSignature Language="VB.NET" Value="Gateway" />
      <MemberSignature Language="F#" Value="Gateway = 0" Usage="Microsoft.Azure.Documents.Client.ConnectionMode.Gateway" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Client.ConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Verwenden Sie das Azure-Cosmos-DB-Gateway, um alle Anforderungen an den Azure-Cosmos-DB-Dienst weiterzuleiten. Die Gateway-Proxys-Anforderungen in der richtigen Datenpartition.
            </summary>
        <remarks>
            Verwenden Sie gatewaykonnektivität, wenn innerhalb der Firewall Settings keine direkte Verbindung zulassen. Alle Verbindungen werden auf dem Datenbankkonto Endpunkt durch die HTTPS-Standardport (Port 443) hergestellt.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>