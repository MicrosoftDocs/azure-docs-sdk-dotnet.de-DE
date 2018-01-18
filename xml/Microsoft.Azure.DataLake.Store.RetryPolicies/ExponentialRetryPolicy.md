<Type Name="ExponentialRetryPolicy" FullName="Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy">
  <TypeSignature Language="C#" Value="public class ExponentialRetryPolicy : Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExponentialRetryPolicy extends Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ExponentialRetryPolicy&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type ExponentialRetryPolicy = class&#xA;    inherit RetryPolicy" />
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
            <span data-ttu-id="8b4ba-101">Exponentielle wiederholungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="8b4ba-101">Exponential retry policy</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExponentialRetryPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8b4ba-102">Standardeinstellungen des exponentiellen wiederholungsrichtlinien</span><span class="sxs-lookup"><span data-stu-id="8b4ba-102">Default settings of Exponential retry policies</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExponentialRetryPolicy (int maxRetries, int interval);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 maxRetries, int32 interval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy.#ctor(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxRetries As Integer, interval As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy : int * int -&gt; Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy" Usage="new Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy (maxRetries, interval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxRetries" Type="System.Int32" />
        <Parameter Name="interval" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxRetries"><span data-ttu-id="8b4ba-103">Maximale Wiederholungsversuche</span><span class="sxs-lookup"><span data-stu-id="8b4ba-103">Maximum retries</span></span></param>
        <param name="interval"><span data-ttu-id="8b4ba-104">Exponentielle Zeitintervall</span><span class="sxs-lookup"><span data-stu-id="8b4ba-104">Exponential time interval</span></span></param>
        <summary>
            <span data-ttu-id="8b4ba-105">Exponentielle wiederholungsrichtlinien mit angegebene maximale Wiederholungsversuche und das Intervall</span><span class="sxs-lookup"><span data-stu-id="8b4ba-105">Exponential retry policies with specified maximum retries and interval</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public override bool ShouldRetry (int httpCode, Exception ex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool ShouldRetry(int32 httpCode, class System.Exception ex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy.ShouldRetry(System.Int32,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ShouldRetry (httpCode As Integer, ex As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="override this.ShouldRetry : int * Exception -&gt; bool" Usage="exponentialRetryPolicy.ShouldRetry (httpCode, ex)" />
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
        <param name="httpCode"><span data-ttu-id="8b4ba-106">HTTP-Statuscode:</span><span class="sxs-lookup"><span data-stu-id="8b4ba-106">Http status code</span></span></param>
        <param name="ex"><span data-ttu-id="8b4ba-107">Letzte Ausnahme, die während der Httprequest Filtermenü</span><span class="sxs-lookup"><span data-stu-id="8b4ba-107">Last exception that we saw during Httprequest</span></span></param>
        <summary>
            <span data-ttu-id="8b4ba-108">Bestimmt, ob sich exponentiell wiederholt</span><span class="sxs-lookup"><span data-stu-id="8b4ba-108">Determines whether to retry exponentially</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>