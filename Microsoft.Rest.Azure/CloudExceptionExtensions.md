<Type Name="CloudExceptionExtensions" FullName="Microsoft.Rest.Azure.CloudExceptionExtensions">
  <TypeSignature Language="C#" Value="public static class CloudExceptionExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CloudExceptionExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Rest.Azure.CloudExceptionExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CloudExceptionExtensions" />
  <TypeSignature Language="F#" Value="type CloudExceptionExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="84c1f-101">Definiert Erweiterungsmethoden für die CloudException-Klasse.</span><span class="sxs-lookup"><span data-stu-id="84c1f-101">Defines extension methods for the CloudException class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="IsAccessConditionFailed">
      <MemberSignature Language="C#" Value="public static bool IsAccessConditionFailed (this Microsoft.Rest.Azure.CloudException exception);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsAccessConditionFailed(class Microsoft.Rest.Azure.CloudException exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Rest.Azure.CloudExceptionExtensions.IsAccessConditionFailed(Microsoft.Rest.Azure.CloudException)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsAccessConditionFailed (exception As CloudException) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsAccessConditionFailed : Microsoft.Rest.Azure.CloudException -&gt; bool" Usage="Microsoft.Rest.Azure.CloudExceptionExtensions.IsAccessConditionFailed exception" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="Microsoft.Rest.Azure.CloudException" RefType="this" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="84c1f-102">Die Ausnahme überprüft.</span><span class="sxs-lookup"><span data-stu-id="84c1f-102">The exception to check.</span></span></param>
        <summary>
            <span data-ttu-id="84c1f-103">Gibt an, ob die Ausnahme das Ergebnis einer fehlerhaften Bedingung (ETag) zugriffsüberprüfung ist.</span><span class="sxs-lookup"><span data-stu-id="84c1f-103">Indicates whether the exception is the result of a failed access condition (ETag) check.</span></span>
            </summary>
        <returns><span data-ttu-id="84c1f-104">"true", wenn die Ausnahme einer fehlerhaften zugriffsbedingung (HTTP 412 Precondition Failed), "false", andernfalls ist.</span><span class="sxs-lookup"><span data-stu-id="84c1f-104">true if the exception is a failed access condition (HTTP 412 Precondition Failed), false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>