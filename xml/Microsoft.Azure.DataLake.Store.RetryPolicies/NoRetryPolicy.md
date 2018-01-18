<Type Name="NoRetryPolicy" FullName="Microsoft.Azure.DataLake.Store.RetryPolicies.NoRetryPolicy">
  <TypeSignature Language="C#" Value="public class NoRetryPolicy : Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NoRetryPolicy extends Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.RetryPolicies.NoRetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class NoRetryPolicy&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type NoRetryPolicy = class&#xA;    inherit RetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ed34c-101">Keine wiederholungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="ed34c-101">No retry policy</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NoRetryPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RetryPolicies.NoRetryPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public override bool ShouldRetry (int httpCode, Exception ex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool ShouldRetry(int32 httpCode, class System.Exception ex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RetryPolicies.NoRetryPolicy.ShouldRetry(System.Int32,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ShouldRetry (httpCode As Integer, ex As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="override this.ShouldRetry : int * Exception -&gt; bool" Usage="noRetryPolicy.ShouldRetry (httpCode, ex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpCode" Type="System.Int32" />
        <Parameter Name="ex" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="httpCode"><span data-ttu-id="ed34c-102">HTTP-Code</span><span class="sxs-lookup"><span data-stu-id="ed34c-102">Http Code</span></span></param>
        <param name="ex"><span data-ttu-id="ed34c-103">Letzte Ausnahme, die während der Httprequest Filtermenü</span><span class="sxs-lookup"><span data-stu-id="ed34c-103">Last exception that we saw during Httprequest</span></span></param>
        <summary>
            <span data-ttu-id="ed34c-104">Immer "false" zurück "</span><span class="sxs-lookup"><span data-stu-id="ed34c-104">Returns false always</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>