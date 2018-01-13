<Type Name="ListAssignmentsFilterParameters" FullName="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters">
  <TypeSignature Language="C#" Value="public class ListAssignmentsFilterParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ListAssignmentsFilterParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ListAssignmentsFilterParameters" />
  <TypeSignature Language="F#" Value="type ListAssignmentsFilterParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Rolle Zuweisungen Listenfilter.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListAssignmentsFilterParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ListAssignmentsFilterParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AssignedToPrincipalId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; AssignedToPrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; AssignedToPrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.AssignedToPrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property AssignedToPrincipalId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.AssignedToPrincipalId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.AssignedToPrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Gibt die rollenzuweisungen, die Ihr unmittelbar zugewiesen werden Prinzipal als auch Aufgaben auf dem Prinzipal Gruppen (transitiv) zurück. Gegenwärtig unterstützt nur für Benutzerprinzipalen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AtScope">
      <MemberSignature Language="C#" Value="public bool AtScope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AtScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.AtScope" />
      <MemberSignature Language="VB.NET" Value="Public Property AtScope As Boolean" />
      <MemberSignature Language="F#" Value="member this.AtScope : bool with get, set" Usage="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.AtScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Dadurch werden alle rollenzuweisungen entspricht bzw. oberhalb zurückgegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; PrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; PrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.PrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property PrincipalId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.PrincipalId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters.PrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Gibt die rollenzuweisung des bestimmten Prinzipals zurück.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>