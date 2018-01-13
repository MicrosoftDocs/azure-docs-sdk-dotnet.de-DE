<Type Name="ConnectionOptions" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions">
  <TypeSignature Language="C#" Value="public enum ConnectionOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectionOptions extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectionOptions" />
  <TypeSignature Language="F#" Value="type ConnectionOptions = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="76225-101">Ermöglicht Benutzern die Angabe der Vorgänge, z. B. Validierung, führen Sie für die Verbindung von der shardzuordnungs-Manager geöffnet.</span><span class="sxs-lookup"><span data-stu-id="76225-101">Allows users to specify operations such as validation, to perform on the connection opened by the shard map manager.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="76225-102">Klicken Sie auf die geöffnete Verbindung wird kein Vorgang ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="76225-102">No operation will be performed on the opened connection.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="Validate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions Validate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />
      <MemberSignature Language="VB.NET" Value="Validate" />
      <MemberSignature Language="F#" Value="Validate = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="76225-103">Überprüfung wird ausgeführt werden, für die Verbindung, um sicherzustellen, dass der Zustand der entsprechenden Zuordnung nicht geändert hat, da die Zuordnungsinformationen zuletzt auf dem Client zwischengespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="76225-103">Validation will be performed on the connection to ensure that the state of the corresponding mapping has not changed since the mapping information was last cached at the client.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>