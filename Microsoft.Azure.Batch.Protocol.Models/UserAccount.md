<Type Name="UserAccount" FullName="Microsoft.Azure.Batch.Protocol.Models.UserAccount">
  <TypeSignature Language="C#" Value="public class UserAccount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserAccount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.UserAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class UserAccount" />
  <TypeSignature Language="F#" Value="type UserAccount = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eigenschaften, die zum Erstellen eines Benutzers zum Ausführen von Aufgaben auf einem Azure Batch-Knoten verwendet werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.UserAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der UserAccount-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccount (string name, string password, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; elevationLevel = null, Microsoft.Azure.Batch.Protocol.Models.LinuxUserConfiguration linuxUserConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string password, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; elevationLevel, class Microsoft.Azure.Batch.Protocol.Models.LinuxUserConfiguration linuxUserConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.UserAccount.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ElevationLevel},Microsoft.Azure.Batch.Protocol.Models.LinuxUserConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.UserAccount : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; * Microsoft.Azure.Batch.Protocol.Models.LinuxUserConfiguration -&gt; Microsoft.Azure.Batch.Protocol.Models.UserAccount" Usage="new Microsoft.Azure.Batch.Protocol.Models.UserAccount (name, password, elevationLevel, linuxUserConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="elevationLevel" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt;" />
        <Parameter Name="linuxUserConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.LinuxUserConfiguration" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Benutzerkontos.</param>
        <param name="password">Das Kennwort für das Benutzerkonto</param>
        <param name="elevationLevel">Die Erhöhung der Rechte Ebene des Benutzerkontos.</param>
        <param name="linuxUserConfiguration">Die Konfiguration der Linux-spezifische für das Benutzerkonto an.</param>
        <summary>
            Initialisiert eine neue Instanz der UserAccount-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElevationLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; ElevationLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; ElevationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UserAccount.ElevationLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ElevationLevel As Nullable(Of ElevationLevel)" />
      <MemberSignature Language="F#" Value="member this.ElevationLevel : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UserAccount.ElevationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="elevationLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt diesen fest die Erhöhung der Rechte des Benutzerkontos.
            </summary>
        <value>To be added.</value>
        <remarks>
            NonAdmin - der Auto-Benutzer ist ein Standardbenutzer ohne erhöhte Zugriffsrechte. Admin - der Auto-Benutzer ist ein Benutzer mit erweiterten Zugriff und arbeitet mit vollständigen Administratorberechtigungen. Der Standardwert ist NonAdmin. Folgende Werte sind möglich: "NonAdmin", "Admin"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxUserConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.LinuxUserConfiguration LinuxUserConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.LinuxUserConfiguration LinuxUserConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UserAccount.LinuxUserConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxUserConfiguration As LinuxUserConfiguration" />
      <MemberSignature Language="F#" Value="member this.LinuxUserConfiguration : Microsoft.Azure.Batch.Protocol.Models.LinuxUserConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UserAccount.LinuxUserConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="linuxUserConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.LinuxUserConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die Linux-spezifische Benutzerkonfiguration für das Benutzerkonto an.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird ignoriert, wenn für einen Windows-Pool angegeben. Wenn nicht angegeben ist, wird der Benutzer mit den Standardoptionen erstellt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UserAccount.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UserAccount.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Benutzerkontos ein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UserAccount.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UserAccount.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Kennwort für das Benutzerkonto fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.UserAccount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="userAccount.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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