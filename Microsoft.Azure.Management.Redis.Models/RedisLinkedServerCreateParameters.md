<Type Name="RedisLinkedServerCreateParameters" FullName="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters">
  <TypeSignature Language="C#" Value="public class RedisLinkedServerCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisLinkedServerCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisLinkedServerCreateParameters" />
  <TypeSignature Language="F#" Value="type RedisLinkedServerCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Der Parameter für das Erstellen eines Verbindungsservers zu redis-Cache erforderlich.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisLinkedServerCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RedisLinkedServerCreateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisLinkedServerCreateParameters (string linkedRedisCacheId, string linkedRedisCacheLocation, Microsoft.Azure.Management.Redis.Models.ReplicationRole serverRole);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string linkedRedisCacheId, string linkedRedisCacheLocation, valuetype Microsoft.Azure.Management.Redis.Models.ReplicationRole serverRole) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.#ctor(System.String,System.String,Microsoft.Azure.Management.Redis.Models.ReplicationRole)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedRedisCacheId As String, linkedRedisCacheLocation As String, serverRole As ReplicationRole)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters : string * string * Microsoft.Azure.Management.Redis.Models.ReplicationRole -&gt; Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters" Usage="new Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters (linkedRedisCacheId, linkedRedisCacheLocation, serverRole)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedRedisCacheId" Type="System.String" />
        <Parameter Name="linkedRedisCacheLocation" Type="System.String" />
        <Parameter Name="serverRole" Type="Microsoft.Azure.Management.Redis.Models.ReplicationRole" />
      </Parameters>
      <Docs>
        <param name="linkedRedisCacheId">Vollqualifizierte Ressourcen-ID des verknüpften Redis-Cache.</param>
        <param name="linkedRedisCacheLocation">Der Speicherort des verknüpften Redis-Caches.</param>
        <param name="serverRole">Die Rolle des Verbindungsservers. Folgende Werte sind möglich: 'Primary', 'Sekundären'</param>
        <summary>
            Initialisiert eine neue Instanz der RedisLinkedServerCreateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedRedisCacheId">
      <MemberSignature Language="C#" Value="public string LinkedRedisCacheId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedRedisCacheId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.LinkedRedisCacheId" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedRedisCacheId As String" />
      <MemberSignature Language="F#" Value="member this.LinkedRedisCacheId : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.LinkedRedisCacheId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedRedisCacheId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest vollqualifizierten ResourceId des verknüpften Redis-Caches.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedRedisCacheLocation">
      <MemberSignature Language="C#" Value="public string LinkedRedisCacheLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedRedisCacheLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.LinkedRedisCacheLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedRedisCacheLocation As String" />
      <MemberSignature Language="F#" Value="member this.LinkedRedisCacheLocation : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.LinkedRedisCacheLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedRedisCacheLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Position des verknüpften Redis-Caches.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerRole">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Models.ReplicationRole ServerRole { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Redis.Models.ReplicationRole ServerRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.ServerRole" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerRole As ReplicationRole" />
      <MemberSignature Language="F#" Value="member this.ServerRole : Microsoft.Azure.Management.Redis.Models.ReplicationRole with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.ServerRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverRole")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.ReplicationRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Rolle des Verbindungsservers. Folgende Werte sind möglich: 'Primary', 'Sekundären'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redisLinkedServerCreateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>