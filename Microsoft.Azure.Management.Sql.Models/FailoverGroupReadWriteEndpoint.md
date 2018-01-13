<Type Name="FailoverGroupReadWriteEndpoint" FullName="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint">
  <TypeSignature Language="C#" Value="public class FailoverGroupReadWriteEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverGroupReadWriteEndpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverGroupReadWriteEndpoint" />
  <TypeSignature Language="F#" Value="type FailoverGroupReadWriteEndpoint = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Lese-/ Schreibzugriff Endpunkt der Gruppeninstanz Failover.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupReadWriteEndpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der FailoverGroupReadWriteEndpoint-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupReadWriteEndpoint (string failoverPolicy, Nullable&lt;int&gt; failoverWithDataLossGracePeriodMinutes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string failoverPolicy, valuetype System.Nullable`1&lt;int32&gt; failoverWithDataLossGracePeriodMinutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (failoverPolicy As String, Optional failoverWithDataLossGracePeriodMinutes As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint" Usage="new Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint (failoverPolicy, failoverWithDataLossGracePeriodMinutes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="failoverPolicy" Type="System.String" />
        <Parameter Name="failoverWithDataLossGracePeriodMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="failoverPolicy">Failoverrichtlinie für den Lese-/ Schreibzugriff-Endpunkt für die Failover-Gruppe. Wenn FailoverPolicy automatisch festgelegt ist, ist FailoverWithDataLossGracePeriodMinutes erforderlich. Folgende Werte sind möglich: 'Manual', 'Automatic'</param>
        <param name="failoverWithDataLossGracePeriodMinutes">Toleranzperiode vor dem Failover ohne Datenverlust wird versucht, für den Endpunkt Lese-/ Schreibzugriff. Wenn FailoverPolicy automatisch festgelegt ist, ist FailoverWithDataLossGracePeriodMinutes erforderlich.</param>
        <summary>
            Initialisiert eine neue Instanz der FailoverGroupReadWriteEndpoint-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverPolicy">
      <MemberSignature Language="C#" Value="public string FailoverPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailoverPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property FailoverPolicy As String" />
      <MemberSignature Language="F#" Value="member this.FailoverPolicy : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failoverPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Failoverrichtlinie für den Lese-/ Schreibzugriff-Endpunkt für die Failover-Gruppe. Wenn FailoverPolicy automatisch festgelegt ist, ist FailoverWithDataLossGracePeriodMinutes erforderlich. Folgende Werte sind möglich: 'Manual', 'Automatic'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverWithDataLossGracePeriodMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FailoverWithDataLossGracePeriodMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FailoverWithDataLossGracePeriodMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverWithDataLossGracePeriodMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property FailoverWithDataLossGracePeriodMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FailoverWithDataLossGracePeriodMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverWithDataLossGracePeriodMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failoverWithDataLossGracePeriodMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Toleranzperiode vor dem Failover mit Verlust von Daten für den Lese-/ Schreibzugriff Endpunkt versucht wird. Wenn FailoverPolicy automatisch festgelegt ist, ist FailoverWithDataLossGracePeriodMinutes erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="failoverGroupReadWriteEndpoint.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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