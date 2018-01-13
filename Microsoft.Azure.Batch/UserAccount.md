<Type Name="UserAccount" FullName="Microsoft.Azure.Batch.UserAccount">
  <TypeSignature Language="C#" Value="public class UserAccount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserAccount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.UserAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class UserAccount" />
  <TypeSignature Language="F#" Value="type UserAccount = class&#xA;    interface ITransportObjectProvider&lt;UserAccount&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Ein Benutzerkonto auf einem Azure Batch-Knoten zu erstellen. Tasks können so konfiguriert werden, um im Sicherheitskontext des Benutzerkontos ausgeführt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccount (string name, string password, Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; elevationLevel = null, Microsoft.Azure.Batch.LinuxUserConfiguration linuxUserConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string password, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ElevationLevel&gt; elevationLevel, class Microsoft.Azure.Batch.LinuxUserConfiguration linuxUserConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.UserAccount.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ElevationLevel},Microsoft.Azure.Batch.LinuxUserConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.UserAccount : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; * Microsoft.Azure.Batch.LinuxUserConfiguration -&gt; Microsoft.Azure.Batch.UserAccount" Usage="new Microsoft.Azure.Batch.UserAccount (name, password, elevationLevel, linuxUserConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="elevationLevel" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt;" />
        <Parameter Name="linuxUserConfiguration" Type="Microsoft.Azure.Batch.LinuxUserConfiguration" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Benutzerkontos.</param>
        <param name="password">Das Kennwort für das Benutzerkonto</param>
        <param name="elevationLevel">Die Erhöhung der Rechte Ebene des Benutzerkontos.</param>
        <param name="linuxUserConfiguration">Zusätzliche Eigenschaften, die zum Erstellen eines Benutzerkontos auf einem Linux-Knoten verwendet werden.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.UserAccount" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElevationLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; ElevationLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ElevationLevel&gt; ElevationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.ElevationLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ElevationLevel As Nullable(Of ElevationLevel)" />
      <MemberSignature Language="F#" Value="member this.ElevationLevel : Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; with get, set" Usage="Microsoft.Azure.Batch.UserAccount.ElevationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt diesen fest die Erhöhung der Rechte des Benutzerkontos.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn nicht angegeben, ist die Standardeinstellung<see cref="F:Microsoft.Azure.Batch.Common.ElevationLevel.NonAdmin" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxUserConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.LinuxUserConfiguration LinuxUserConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.LinuxUserConfiguration LinuxUserConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.LinuxUserConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxUserConfiguration As LinuxUserConfiguration" />
      <MemberSignature Language="F#" Value="member this.LinuxUserConfiguration : Microsoft.Azure.Batch.LinuxUserConfiguration with get, set" Usage="Microsoft.Azure.Batch.UserAccount.LinuxUserConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.LinuxUserConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt weitere Eigenschaften, die zum Erstellen eines Benutzerkontos auf einem Linux-Knoten verwendet.
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Batch.UserAccount.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.UserAccount.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
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
  </Members>
</Type>