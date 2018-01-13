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
            <span data-ttu-id="0fda1-101">Rolle Zuweisungen Listenfilter.</span><span class="sxs-lookup"><span data-stu-id="0fda1-101">List role assignments filter.</span></span>
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
            <span data-ttu-id="0fda1-102">Initialisiert eine neue Instanz der ListAssignmentsFilterParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0fda1-102">Initializes a new instance of the ListAssignmentsFilterParameters class.</span></span>
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
            <span data-ttu-id="0fda1-103">Optional.</span><span class="sxs-lookup"><span data-stu-id="0fda1-103">Optional.</span></span> <span data-ttu-id="0fda1-104">Gibt die rollenzuweisungen, die Ihr unmittelbar zugewiesen werden Prinzipal als auch Aufgaben auf dem Prinzipal Gruppen (transitiv) zurück.</span><span class="sxs-lookup"><span data-stu-id="0fda1-104">Returns role assignments directly assigned to the principal as well as assignments to the principal's groups (transitive).</span></span> <span data-ttu-id="0fda1-105">Gegenwärtig unterstützt nur für Benutzerprinzipalen</span><span class="sxs-lookup"><span data-stu-id="0fda1-105">Currenly supported only for User Principals</span></span>
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
            <span data-ttu-id="0fda1-106">Optional.</span><span class="sxs-lookup"><span data-stu-id="0fda1-106">Optional.</span></span> <span data-ttu-id="0fda1-107">Dadurch werden alle rollenzuweisungen entspricht bzw. oberhalb zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="0fda1-107">This returns all role assignments at or above.</span></span>
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
            <span data-ttu-id="0fda1-108">Optional.</span><span class="sxs-lookup"><span data-stu-id="0fda1-108">Optional.</span></span> <span data-ttu-id="0fda1-109">Gibt die rollenzuweisung des bestimmten Prinzipals zurück.</span><span class="sxs-lookup"><span data-stu-id="0fda1-109">Returns role assignment of the specific principal.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>